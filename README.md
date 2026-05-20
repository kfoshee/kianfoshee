# kianfoshee.com

Static personal website hosted on GitHub Pages.

## Run locally

```bash
python3 -m http.server 3000
```

Then open http://localhost:3000

## Deploy

Push to GitHub. GitHub Pages serves from the `main` branch root folder.

```bash
git add .
git commit -m "Update site"
git push
```

## Custom domain

- Domain: **kianfoshee.com**
- DNS provider: **Porkbun**
- Configured via the `CNAME` file at the repo root.
