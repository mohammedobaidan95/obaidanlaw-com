# Al Obaidan Law Firm — Website

Production website for Al Obaidan Law Firm, Doha.

## Structure

- `index.html` — the entire site (single-page application with client-side navigation)
- `images/` — all photography, portraits, and the firm logo
- `.nojekyll` — tells GitHub Pages to serve files directly

## Editing content

All content is in `index.html`. To edit text (bios, matter descriptions, contact details, etc.):

1. Open `index.html` on GitHub
2. Click the pencil icon to edit
3. Find the text you want to change (use Ctrl+F / Cmd+F)
4. Edit it
5. Scroll to the bottom, write a short note ("Updated Mohammed's bio"), click Commit
6. GitHub Pages will redeploy automatically within 1–2 minutes

## Adding a new Insights article

Find the Insights section in `index.html`. Duplicate one of the existing `<article class="insight">` blocks and change the date, title, and body text.

## Replacing a photo

Upload the new photo to the `images/` folder with the same filename. The site will pick it up automatically.

## Domain

The site is served at `obaidanlaw.com`. DNS settings point to GitHub Pages.
