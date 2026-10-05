# MOVICI Website V1.2 — Update

This version updates the existing MOVICI website without changing its overall design.

Changes:
- added a **Support** section to the homepage;
- expanded **Funding** into **Funding & Institutional Support**;
- added official links for Université Côte d’Azur, MSHS Sud-Est, CoCoLab, MSI, DS4H, and RISE;
- added the English rendering of RISE: **Academy of Excellence “Networks, Information and Digital Society”**;
- corrected the homepage Quarto YAML header;
- preserved the Google verification file;
- moved the validated sitemap into the Quarto project resources so future renders retain it;
- removed `docs/` from `.gitignore`, because `docs/` is now the GitHub Pages publication directory.

## Publication workflow

After replacing your local project with this version (or copying the changed files), run:

```bash
quarto render
git add .
git status
git commit -m "Update funding and institutional support"
git push origin main
```

GitHub Pages is configured to publish from `main /docs`.
