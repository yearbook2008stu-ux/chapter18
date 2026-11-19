# CHAPTER.18 Photo Frame Editor

Static HTML/CSS/JavaScript app prepared for GitHub Pages.

## Deploy
1. Create a new GitHub repository (for example `chapter18-photo-editor`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in Settings → Pages.

## Notes
- The app runs in the browser and uses IndexedDB for locally saved custom frame templates.
- Custom templates are stored in the browser/device that created them; they are not automatically shared between visitors.
- For shared studio-wide frame management, connect a backend/database and authentication.
