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

## Custom domain (optional)

Both hosts support a custom domain on their free tier. Buy a domain (~$10/year), then add
the DNS records the host specifies in its domain settings, and enable HTTPS.

## Methodology

Inclusion requires official documentation (government records, commission or task-force
reports, court findings, statutes). Figures are recorded as ranges where sources genuinely
disagree, never as false precision. A blank apology/reparations field means "none located,"
not "confirmed absent." Full methodology notes are in the accompanying spreadsheet.
