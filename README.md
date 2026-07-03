# Maui Smart Homes — Website

A single-page site for Maui Smart Homes, a Maui-based home automation & AV integration company. Pure HTML/CSS/JS — no build step, no dependencies.

## Files

- `index.html` — the entire site (markup, styles, and the mobile-menu script are all in this one file)
- `assets/logo.png` — full brand mark (icon + wordmark), used in the hero
- `assets/icon.png` — cropped icon-only mark, used in the nav, footer, and favicon

## Edit the content

Open `index.html` in any text editor. Everything is plain HTML — search for the text you want to change (phone number, email, stats, service area, etc.) and edit it directly. The four stat numbers, the four "Our principles" cards, and the contact details near the bottom are the easiest places to start.

## Push it to GitHub

```bash
git init
git add index.html README.md assets
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

(Create the empty repo on GitHub first, then run the commands above from the folder containing `index.html`.)

## Deploy on Netlify

**Option A — connect the repo (recommended, auto-redeploys on every push):**
1. Go to [app.netlify.com](https://app.netlify.com) and log in.
2. Click **Add new site → Import an existing project**.
3. Choose **GitHub**, authorize Netlify, and select your repo.
4. Build settings: leave **Build command** blank and set **Publish directory** to `.` (the repo root, since `index.html` lives there).
5. Click **Deploy site**. Netlify gives you a live URL immediately (e.g. `random-name-123.netlify.app`), which you can rename or point a custom domain at under **Site settings → Domain management**.

**Option B — drag and drop (fastest, no GitHub required):**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the folder containing `index.html` onto the page.
3. Done — Netlify hosts it instantly. (You can still connect it to GitHub later for auto-deploys.)

## Notes

- The site is fully responsive and has a mobile nav toggle built in — no extra setup needed.
- Fonts (Fraunces, Inter, Space Mono) load from Google Fonts via CDN — no local font files to manage.
- Placeholder contact info (`(808) 555-0142`, `aloha@mauismarthomes.com`) should be swapped for the real details before going live.
