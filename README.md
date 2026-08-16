# Jagdish Tour Travels — Deployed Site

This repository contains a simple single-page starter site (index.html) built with Tailwind CSS (via CDN).

Automatic deployment

This repo includes a GitHub Actions workflow that deploys the repository contents to GitHub Pages on every push to the `main` branch. The workflow file is `.github/workflows/pages.yml` and uses the official GitHub Pages actions.

Once the workflow finishes, the site will be available at:

https://naresh7740.github.io/Jagdish-tour-travels/

If you don't see the site immediately, give the Actions workflow 1–2 minutes to complete. If the repo is private, GitHub Pages will not publish unless you change the repository visibility to public or use a different hosting provider.

Local preview

1. Clone the repo:
   ```bash
   git clone https://github.com/naresh7740/Jagdish-tour-travels.git
   cd Jagdish-tour-travels
   ```
2. Run a local server:
   - Python 3: `python -m http.server 8000`
   - Node: `npx serve`
3. Open `http://localhost:8000` in your browser.

Customize

- Edit `index.html` to change content, images, or contact email.
- Add additional assets (images, styles) and push to `main` — the workflow will redeploy automatically.

If you want me to also add a CNAME for a custom domain, create a `CNAME` file in the repo or tell me the domain and I’ll add it and update the workflow if required.
