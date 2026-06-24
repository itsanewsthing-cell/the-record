# The Record — Documented U.S. Government Atrocities & Apologies, 1776–2026

A self-contained, interactive single-page record of documented atrocities and destructive
programs committed by U.S. federal, state, territorial, or local governments against people
under U.S. jurisdiction, tracking whether each was ever formally apologized for and whether
any reparations were provided.

The page is a single static HTML file (`index.html`) with no backend, no build step, and
no external network calls — all data, styles, and scripts are embedded. It runs by opening
the file in any modern browser.

## What's in this repo

- `index.html` — the entire site (data + interface in one file).
- `404.html` — a styled "page not found" page matching the site's design.
- `.nojekyll` — tells GitHub Pages to serve the files as-is, skipping Jekyll processing.
- `README.md` — this file.

## Deploying to GitHub Pages (free)

1. Create a public repository and upload these files to its root.
2. In the repository's **Settings → Pages**, set the source to **Deploy from a branch**,
   branch `main`, folder `/ (root)`, and save.
3. The site goes live at `https://USERNAME.github.io/REPO/` within a minute or two.
   (Naming the repo `USERNAME.github.io` serves it at the root instead.)

## Deploying to Vercel (free Hobby tier — personal/non-commercial use)

1. Sign up at vercel.com (the "Continue with GitHub" option is easiest).
2. **Add New → Project → Import** this repository, then **Deploy**.
3. The site goes live at `https://PROJECT.vercel.app`. Every commit auto-redeploys.

Note: Vercel's free Hobby plan is for personal, non-commercial use. Adding anything
commercial (ads, donations, paid features) would require a paid plan — verify against
Vercel's current terms before adding such features.

## Custom domain (optional)

Both hosts support a custom domain on their free tier. Buy a domain (~$10/year), then add
the DNS records the host specifies in its domain settings, and enable HTTPS.

## Methodology

Inclusion requires official documentation (government records, commission or task-force
reports, court findings, statutes). Figures are recorded as ranges where sources genuinely
disagree, never as false precision. A blank apology/reparations field means "none located,"
not "confirmed absent." Full methodology notes are in the accompanying spreadsheet.
