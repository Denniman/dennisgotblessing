# Dennis & Blessing — Wedding Programme

A single-page wedding programme for Dennis & Blessing's wedding on **Saturday, 26th September 2026**.

`#DennisGotHisBlessing2026`

## What's here

- `index.html` — the entire site (markup, styles, and script inline, self-contained)
- `images/` — original couple photos
- `images/web/` — compressed, web-sized copies of those photos actually used by the page

## Running it locally

No build step. Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deploying to GitHub Pages

```bash
git init
git add .
git commit -m "Add wedding programme"
git branch -M main
git remote add origin https://github.com/<your-username>/dennisgotblessing.git
git push -u origin main
```

Then in the repo on GitHub: **Settings → Pages** → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`.

The site will publish at:

```
https://<your-username>.github.io/dennisgotblessing/
```

Once that URL is live, generate a QR code for it to share on invitations and at the venue.
