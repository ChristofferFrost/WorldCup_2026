# WorldCup_2026 — VM 2026 Bet Tracker

This repository contains a standalone HTML app (single file) that tracks predictions and scores for a World Cup 2026 bet game between Frost, Viggo and Oscar.

Files
- `index.html` — the website. Open it in a browser locally or host it with GitHub Pages.

Publish with GitHub Pages (root of `main` branch)
1. Commit and push this repository to GitHub.
2. In the repository Settings → Pages, select the `main` branch and the `/ (root)` folder and save.
3. After a minute, your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Notes
- The app stores results and predictions in browser `localStorage`. Admin actions are protected by a simple PIN inside the page (change `ADMIN_PIN` in `index.html` if needed). This is fine for private use but not secure for public multi-user editing.
- If you want live automatic updates from a football API, you'll need a small server or function to fetch the API and update the page or provide endpoints.

Preview locally
- Simply open `index.html` in your browser. For a better simulation of GitHub Pages, serve the folder with a static server, e.g. with Python 3 installed:

```bash
# run from repository root
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Small improvements you might want next
- Add a tiny GitHub Action to automatically deploy to Pages or update results from an API (requires storing API keys securely).
- Split CSS/JS into separate files for easier edits and caching.

If you want, I can add those optional improvements.
