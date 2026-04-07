# Public Dashboard Site Export

This folder is the separate public GitHub Pages repository.

## Files included
- `index.html`
- `longevity-explorer.html`
- `aging_biomarkers_dashboard.html`
- `aging_biomarkers_public/`
- `data/series/` for the curated biomarker subset only

## Suggested refresh flow
1. Rebuild the audience-facing dashboard in `nhanes_dashboard`.
2. Run `python3 scripts/export_public_dashboard_site.py` from the main repo.
3. Commit and push the updated files in this repo.

## Notes
- This export includes only the files needed by the audience-facing dashboard.
- It does not include the full analysis repo, source notebooks, or unrelated dashboard assets.
- The dashboard expects `aging_biomarkers_public/` and `data/series/` to live next to the HTML files.
