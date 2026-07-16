# PocketWave Operating Dashboard

A public, editable finance and operations dashboard built from the PocketWave case-study data.

## Public site

Expected URL after GitHub Pages is enabled:

`https://aovaktiv.github.io/pocketwave-dashboard/`

One-time setup: open **Settings → Pages** in this repository and set the source to **GitHub Actions**. The included workflow deploys every push to `main`.

## Files

- `index.html` — executive dashboard
- `editor.html` — browser-based source-data editor
- `source_data.csv` — editable inputs
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment

## Updating the data

1. Open `editor.html` from the public site.
2. Change the source values and download the revised `source_data.csv`.
3. Replace `source_data.csv` in this repository and commit the change.
4. GitHub Pages redeploys automatically and the dashboard reads the updated CSV on its next load.

Percentages are stored as decimals, so `0.20` means 20%. Do not rename the keys unless the dashboard code is updated to match.

All data in this public repository should be treated as public. Do not upload credentials, customer-level information, or confidential company data.
