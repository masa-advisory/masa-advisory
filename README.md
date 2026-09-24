# Masa Menswear Advisory website

Static site, ready for GitHub Pages. No build step needed.

## Publish on GitHub Pages
1. Create a new repository on GitHub, for example `masa-advisory`.
2. Upload everything in this folder to the repository root (keep the folder structure: `index.html` must sit at the top level, next to `assets/` and `insights/`).
3. In the repository, go to Settings > Pages.
4. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
5. After a minute or two the site is live at `https://<your-username>.github.io/masa-advisory/`.

## Custom domain (optional)
1. Buy the domain (for example `masa-advisory.sg`).
2. In Settings > Pages, enter the domain under "Custom domain" and save. GitHub adds a `CNAME` file.
3. At your domain registrar, point the domain to GitHub Pages as GitHub's instructions describe, then tick "Enforce HTTPS".

## Files
- `index.html` home page
- `services.html`, `lookbook.html`, `about.html` (includes contact and point of view)
- `insights/` three articles
- `assets/css/style.css` all styling
- `assets/img/` photos, favicon, social preview image

## Contact form
The form opens the visitor's email app with their details filled in, addressed to masa_advisory@zohomail.sg. To receive submissions without an email app, connect a service such as Formspree later.
