# Auto MoM — JSW Motors demo

## Run locally
1. Extract this folder.
2. Open `index.html` in Chrome or Edge, or open the folder in VS Code and use Live Server.
3. Create a meeting, add action items, save, then use Meeting History / Action Tracker.

## Publish with GitHub Pages
1. Create or open your GitHub repository.
2. Upload `index.html` to the repository root (not inside an extra nested folder).
3. Commit/push to the `main` branch.
4. In GitHub, open Settings → Pages.
5. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish, then use the URL shown in Settings → Pages.

## Important demo limitations
- Meeting data is stored in localStorage in the browser used to enter it. It does not automatically sync between different laptops or users.
- This is a front-end demo. It does not yet provide a shared database, authentication, email sending, recording transcription, or AI-generated action extraction.
- For official company use or shared multi-user data, connect it to an approved backend/database and authentication.
