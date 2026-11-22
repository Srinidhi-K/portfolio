# Portfolio (plain HTML/CSS/JS — no build tools, no Node)

Just three files:
- `index.html` — all your content
- `assets/style.css` — colors, spacing, layout (edit `:root` at the top to restyle everything)
- `assets/script.js` — scroll animations + mobile menu

## Edit your content

Open `index.html` in any text editor and replace the placeholder text
("Your Name", "Project One", etc.) with your own. There's no build step —
just save the file.

## Publish it for free with GitHub Pages

1. Create a new repository on GitHub (e.g. `your-portfolio`).
2. Upload these files to it — either drag-and-drop them in the GitHub web
   UI ("Add file → Upload files"), or via git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<you>/<repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   branch `main`, folder `/ (root)`. Click **Save**.
5. Wait about a minute, then your site is live at:
   `https://<you>.github.io/<repo>/`

No npm, no build step, no server to maintain — GitHub just serves the files
directly.
