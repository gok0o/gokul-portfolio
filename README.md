# Gokul M — AI/ML Engineer Portfolio

A responsive, single-page portfolio designed for GitHub Pages, Vercel, or any static host. Built with semantic HTML, CSS, and vanilla JavaScript (no build step or API keys required).

## Run locally

Open `index.html` in a browser, or run a local server from this directory:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to Vercel

1. Create a GitHub repository named `gokul-portfolio`.
2. Upload the contents of this folder to the repository root (not the outer zip folder).
3. In Vercel, choose **Add New → Project**, import `gokul-portfolio`, and deploy.
4. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (or leave the default if Vercel detects the static site).
5. Vercel will provide a public `*.vercel.app` URL after deployment.

## Before sharing

- Verify every project card points to the correct repository. At the moment, project cards point to your GitHub profile because exact repository URLs were not verified from the profile page.
- Replace the resume PDF in `assets/Gokul-M-Resume.pdf` whenever your resume changes.
- Verify dates, metrics, and project descriptions against your latest resume and repositories.

## Included

- `index.html` — content and sections
- `styles.css` — responsive dark theme, lime accent, custom project visuals and motion
- `script.js` — mobile menu, reveal-on-scroll, copy-email interaction
- `assets/Gokul-M-Resume.pdf` — resume download
