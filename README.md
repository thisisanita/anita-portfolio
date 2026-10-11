# Anita Portfolio — Static Site

This is a dependency-free static portfolio built with HTML, CSS and a tiny amount of JavaScript.

## Files
- `index.html` — page structure and copy
- `styles.css` — all layout, typography, color and responsive rules
- `script.js` — mobile navigation only

## Before publishing
1. Replace `YOUR_EMAIL_HERE` in `index.html` with your email address.
2. Replace `YOUR_LINKEDIN_URL_HERE` with your LinkedIn URL.
3. Add your actual resume as `resume.pdf` in this folder, or change the Resume links to your preferred destination.

## Typography
The CSS requests **Kepler / Kepler Std** for headings and **Avenir Light / Avenir Next** for body text. Font files are not bundled. If a visitor does not have these fonts installed, the site falls back to Georgia for headings and Helvetica/Arial for body text. For consistent public rendering, connect your licensed web-font source later.

## Preview locally
Open `index.html` in a browser, or run a simple local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
