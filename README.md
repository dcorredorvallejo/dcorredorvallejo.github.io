# danielcorredorvallejo — personal academic website

Minimal serif three-page site (Home / Research / CV) for Daniel Corredor-Vallejo, ready for GitHub Pages.

## Deploy (one time, ~3 minutes)

1. On GitHub (logged in as **dcorredorvallejo**), create a new **public** repository named exactly:
   `dcorredorvallejo.github.io`
2. On the new repo page: *Add file → Upload files* → drag in everything in this folder
   (`index.html`, `research.html`, `cv.html`, and the `assets/` folder with both files inside) → *Commit changes*.
3. Wait a minute. The site is live at **https://dcorredorvallejo.github.io**
4. If it doesn't appear: *Settings → Pages → Source: Deploy from a branch → main → / (root) → Save*.

## Updating later

- **New CV**: replace `assets/cv.pdf` (keep the filename) — the CV page embeds it automatically.
- **New photo**: replace `assets/profile.jpg` (a ~4:5 portrait crop, e.g. 800×1000 px, looks best).
- **Text edits**: edit the `.html` files directly on GitHub (pencil icon); changes go live within a minute.
- **"Last updated" line**: it appears in the footer of each page — update it when you make changes.

## Before going live — verify

- The Nigeria IDEAS entry (Research page): confirm with the team the byline order (Premand, Crépon,
  Okunogbe, Khan) and the role note about leading the endline analysis work.

## Note on the hosted CV

`assets/cv.pdf` is a web version: the referee list is replaced with "Available upon request." and the
mobile number is removed (true redaction — the text is not recoverable from the file). Keep your full
CV for direct applications; only this hosted copy is public.

## Optional: custom domain

Buy a domain (~US$10–15/yr), then *Settings → Pages → Custom domain*, and add the DNS records GitHub
shows you at your registrar. The github.io address keeps working either way.

## Design notes

EB Garamond (display, small-caps nav) + Source Serif 4 (body). The double rule under the masthead and
the heavy rule above the footer are a nod to booktabs (`\toprule` / `\bottomrule`). Styles are inlined
in each page so every file is self-contained.
