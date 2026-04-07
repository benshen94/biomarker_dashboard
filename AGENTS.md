# Agent Directives

1. **Published Site Repo Only**: This repo is the public, built dashboard repo for GitHub Pages. It is not the source-of-truth repo for dashboard logic, templates, or data processing.
2. **Do Not Build Here First**: Make substantive dashboard edits in `/Users/benshenhar/Library/CloudStorage/GoogleDrive-benshenhar@gmail.com/My Drive/Weizmann/Alon Lab/Aging/nhanes_dashboard`, then export the site into this repo with `python3 scripts/export_public_dashboard_site.py` from that source repo.
3. **What Belongs Here**: Keep only the public static site files here, such as `index.html`, `longevity-explorer.html`, `aging_biomarkers_dashboard.html`, `aging_biomarkers_public/`, `data/series/`, and small repo-level documentation files.
4. **Publish Flow**: After the export refreshes this repo, review the diff, commit with a descriptive message, and push to `main`. GitHub Pages serves this repo directly.
5. **Avoid Manual Drift**: Avoid manual edits here unless the change is truly specific to the published static bundle. Prefer fixing the source repo and re-exporting so the two repos do not drift apart.
