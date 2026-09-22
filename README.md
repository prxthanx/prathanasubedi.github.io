# Prathana Subedi — Creative Portfolio

This VS Code-ready copy preserves the existing portfolio design, layout, styling, animation, images, Figma links, and video collection behavior.

## Open in VS Code

1. Extract this ZIP.
2. Open the **Prathana-Portfolio** folder in VS Code (`File > Open Folder`).
3. When VS Code recommends **Live Server**, install it.
4. Open `index.html`.
5. Click **Go Live** in the bottom-right of VS Code, or right-click `index.html` and choose **Open with Live Server**.
6. The portfolio should open at approximately `http://127.0.0.1:5500/`.

> Do not open `index.html` by double-clicking it as a `file://` page. The portfolio loads `videos.json` with JavaScript, so it should be served through Live Server (or another local web server).

## Main editable files

- `index.html` — portfolio content and layout
- `style.css` — base responsive styling
- `creative.css` — creative typography and visual treatment
- `bright.css` — final bright color-theme layer
- `app.js` — filters, project dialogs, video collection rendering
- `videos.json` — Google Drive video collection data
- `assets/` — images and the directly hosted AR walkthrough video

## Important

- Asset paths are already relative and ready for local/static hosting.
- Google Fonts are loaded from Google and require an internet connection.
- The 37 video edits are opened/embedded from Google Drive, so their original sharing permissions still apply.
- Figma prototype links remain external.
- No build step is required.

## Optional local server without Live Server

If Python is installed, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deployment

This folder is static-site ready for services such as Cloudflare Pages, Netlify, Vercel, or GitHub Pages. Upload/publish the project root so `index.html` is the site entry point.
