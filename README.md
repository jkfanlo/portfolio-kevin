# Jon Kevin Fanlo — Static Portfolio

Deployment-ready static HTML/CSS/JavaScript portfolio.

## GitHub Pages
1. Create a new GitHub repository (recommended: `jonkevinfanlo` or `portfolio`).
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main`, and `/ (root)`.
5. Save and wait for GitHub Pages to publish.

## Cloudflare Pages
1. Push this folder to GitHub.
2. In Cloudflare, open **Workers & Pages → Create → Pages → Connect to Git**.
3. Select the repository.
4. Framework preset: **None**.
5. Build command: leave blank.
6. Build output directory: `/` (repository root).
7. Deploy.

## Custom domain
After buying a domain, add it through your GitHub Pages or Cloudflare Pages project settings. Do not add a CNAME file until the final domain is chosen.

## Main files
- `index.html` — website content
- `style.css` — styling
- `script.js` — mobile navigation
- `assets/jon-kevin-fanlo.png` — profile image
