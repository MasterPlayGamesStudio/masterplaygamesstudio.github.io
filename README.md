# Master Play Games — Company Website

Static website ready for GitHub Pages.

## Edit quickly
- Update company info, social links, and game list in `site_data.json`.
- Replace placeholder SVGs in `assets/img/` with real screenshots (keep file names or update `site_data.json`).

## Local preview
Just open `index.html` in your browser (no build step).

## Deploy to GitHub Pages
1. Create a new repo named `masterplaygames.github.io` (or any name if using Project Pages).
2. Upload all files to the repo root and commit.
3. In **Settings → Pages**, choose source:
   - User/Org Pages: default branch `/ (root)`.
   - Project Pages: default branch `/root` then site is at `https://<username>.github.io/<repo>/`.
4. Wait ~1–2 minutes, then open the URL shown in Pages settings.

## Custom domain (optional)
- Buy a domain, add a `CNAME` file with your domain inside (e.g., `www.masterplaygames.com`).
- In **Settings → Pages**, set the custom domain and add the suggested DNS records.
- GitHub will issue HTTPS automatically.

## Contact form
This template uses a static demo alert. To receive messages:
- Formspree: add the provided endpoint as `action` in the form, or
- Netlify Forms, or
- Send to Firebase via Cloud Functions.

## License
You can use and modify this template freely.
