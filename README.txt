SIKOPDES - Vercel static deployment

Package contains index.html in the project root and public/index.html for common Vercel static output configurations.

Recommended steps:
1. Extract this ZIP.
2. Upload the contents (index.html, public folder, README.txt) to a GitHub repository. Keep the folder structure as-is.
3. In Vercel, import that GitHub repository.
4. Framework Preset: Other.
5. Build Command: leave empty.
6. If Output Directory is set to public, keep it; if deployment still returns 404, set Output Directory to public and redeploy. Do not set Root Directory to a folder that does not contain these files.
7. Deploy and open the Production URL.

Note: the app stores data in localStorage in the current browser. Data does not automatically sync across devices or users and is not stored in a shared database.
