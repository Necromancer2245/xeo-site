# Xeo — Static Site

This is a small static website for the Xeo game store. It includes:

- `home.html` — main page with carousel and game cards
- `download.html` — per-game download pages (use `?game=<id>`)
- `downloads/` — placeholder game files used for testing local downloads

Quick local test

1. Open PowerShell and start a local static server from the project folder:

```powershell
cd C:\XboxGames\xeo
python -m http.server 8000
# then open http://localhost:8000/home.html
```

2. Click a game card → `download.html?game=...`, then click Download to test file delivery.

Deploy options

- GitHub Pages: good for static sites (not ideal for large binaries).
- Netlify / Vercel: easy deploys and HTTPS. Use an external storage (S3) for large files.

If you want, I can initialize a GitHub repo and push this for you (will need your GitHub credentials or `gh` access).