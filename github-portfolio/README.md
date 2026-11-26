# Portfolio

Static portfolio site. All content lives in `data.json`; `index.html` renders it.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for example `portfolio`).
2. Upload `index.html`, `data.json`, `.nojekyll` and `README.md` to the main branch.
3. Go to Settings, then Pages. Under Build and deployment choose "Deploy from a branch", select `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.
   Name the repo `<your-username>.github.io` to get `https://<your-username>.github.io/` instead.

## Update your content
Open `data.json` on GitHub, click the pencil icon, edit the text and commit. The site updates in about a minute.
Keep the JSON valid: text stays in double quotes, items in a list are separated by commas.
Links must start with `https://`. An empty list (`[]`) hides that section.

## Preview locally
Run `python3 -m http.server` in this folder and open http://localhost:8000.
