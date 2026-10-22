# Isamu Okada's Page

Plain HTML site migrated from the WordPress blog at www2.gsid.nagoya-u.ac.jp/blog/isamuokada/.
No JavaScript, no build step, no third-party requests.

## Files
- `index.html` – Profile (home)
- `teaching.html`, `games.html`, `manuals.html`, `data-links.html`
- `ja/index.html` (プロフィール), `ja/works.html` (業績)
- `style.css` – the only stylesheet
- `images/` – photos (metadata stripped)
- `files/` – downloadable documents

## Publish on GitHub Pages
1. Create a public repository (e.g. `<username>.github.io`).
2. Upload everything in this folder (including `.nojekyll`) to the repository root.
3. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)`.
4. Settings → Pages → tick "Enforce HTTPS".

## Editing
Edit a page's `.html` file directly in GitHub (pencil icon) and commit; the site updates in about a minute.
The navigation menu is repeated at the top of each page, so a new page must be added to the menu in every file.
