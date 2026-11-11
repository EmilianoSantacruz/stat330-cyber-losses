# STAT 330: Reported Cyber Incident Losses

Group: Fernanda Lopez, Emiliano Santacruz, and Aidee Mendez.

This repository contains the publishing checkpoint. The interactive AI extension and its two independent checks are planned, not finished.

- Website: https://EmilianoSantacruz.github.io/stat330-cyber-losses/
- Quarto sources: `portfolio/index.qmd` and `portfolio/ai-use.qmd`.
- Rendered website: `portfolio/docs/`.
- Data: the case-study source embeds the 61-record VCDB snapshot and the complete filtering code. No separate download is needed to render it.
- Requirements: R, knitr, rmarkdown, and Quarto.
- Render: run `quarto render` from `portfolio/`.
- Publication: the root `docs/` folder is an exact copy of the rendered `portfolio/docs/` folder so GitHub Pages can publish from `main` and `/docs`.
- Update: render, copy `portfolio/docs/` to root `docs/`, commit both source and output, and push.

Data source: VERIS Community Database, commit f6f98c00f66ab35f5b49977a5852ce94a5bb31d1. Adapted data: CC BY-SA 4.0. Full citations and exclusions appear in the case study.
