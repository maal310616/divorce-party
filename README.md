# DPI Case Review Dashboard

An evidence-led, standalone website for the Divorce Party International takeover accounting case.

## Open locally

Open `index.html` in a browser.

## Publish with GitHub Pages or Vercel

Upload this entire folder to a new GitHub repository. It has no dependencies or build step.

- **GitHub Pages:** select the `main` branch and root folder in Settings → Pages.
- **Vercel:** import the repository and deploy it as a static site; use the default settings.

## Required hand-in routes

After deployment, verify these URLs before submitting:

- `/` — dashboard and reconciliations
- `/review/` — final review of the 25 material judgments, including challenges and statement effects
- `/submission.json` — structured submission record with all 100 decision IDs

Replace `TO_COMPLETE` in `submission.json` with your own name and student ID before handing in.

## Included files

- `index.html` — the complete interactive dashboard
- `review/index.html` — the final-review route
- `submission.json` — the structured hand-in route
- `case-summary.json` — the financial summary and project data
- `CASE-ANALYSIS.md` — a readable evidence-led case analysis
- `vercel.json` — Vercel deployment settings
- `.gitignore` — excludes common local system files
