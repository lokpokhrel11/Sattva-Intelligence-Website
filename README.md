# Sattva Intelligence static site

A six-page static reference website. No build step or server-side code is required.

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Update content

- Edit episode rows in `episodes.html`.
- Add corrections as `<tr>` rows in `corrections.html`. Keep `data-sort` values on date cells in `YYYY-MM-DD` format so sorting remains reliable.
- Shared design rules are in `styles.css`.
- Shared navigation and correction-table sorting are in `site.js`.

## Publish with GitHub Pages

1. Create a GitHub repository and add all files from this folder at the repository root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.

GitHub will provide the public URL after deployment.
