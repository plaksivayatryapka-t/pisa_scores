# PISA mathematics scores

Interactive dashboard: https://plaksivayatryapka-t.github.io/pisa_scores/

One chart of mathematics scores over time, with country and regional-average selection. The dashboard includes assessments through 2025, a fixed 350–550 Y-axis, and individual point tooltips.

## Hosting and updates

GitHub Pages publishes `index.html` from the root of `main`. The HTML contains its data, JavaScript, and CSS; no server, package installation, or build is needed here. `.nojekyll` disables Jekyll processing.

To update the live dashboard, replace `index.html` with the latest exported `dashboard.html`, then commit and push to `main`.

## Data

- OECD PISA 2025, Table I.B1.2a.38: https://stat.link/mrq53f
- Historical-only participants: https://ourworldindata.org/grapher/academic-performance?sex=both&subject=mathematics
- Regional averages are calculated as equal-weight means of countries with results in each assessment cycle. Country coverage varies over time; the chart includes methodology notes.
