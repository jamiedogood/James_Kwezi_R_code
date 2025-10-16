# James_Kwezi_R_code
# R for Data Science — Class Notes (R Markdown)

This repository contains knit‑ready **R Markdown** notebooks extracted from class materials by Dr. Pacifique (notes prepared by James). Each notebook is runnable in a fresh R session.

## Files
- `class1_R_2025.Rmd` — Vectors, data structures, data import, EDA basics
- `class2_R_2025.Rmd` — Data visualisation (base + ggplot2), data management (base R, dplyr)
- `class2_cont_R_2025.Rmd` — Control structures, functions, `apply` family, Titanic tables, aggregation/reshape
- `class4_R_2025.Rmd` — Regression (OLS & polynomial), diagnostics, simulation, sampling, inequality plot

## How to run
1. Install R (and optionally RStudio).
2. Open any `*.Rmd` and click **Knit** (HTML or PDF).  
   Or from terminal:
   ```bash
   Rscript -e "install.packages(c('rmarkdown','ggplot2','dplyr','nycflights13'), repos='https://cloud.r-project.org')"
   Rscript -e "rmarkdown::render('class1_R_2025.Rmd', output_format='html_document')"
   ```

### Packages used
- Core: `rmarkdown`, `knitr`
- Visualization & data: `ggplot2`, `dplyr`, `nycflights13`
- Optional (commented in code): `reshape2`

## Repo structure
```
.
├─ class1_R_2025.Rmd
├─ class2_R_2025.Rmd
├─ class2_cont_R_2025.Rmd
├─ class4_R_2025.Rmd
├─ README.md
└─ .gitignore
```

## Notes
- All external file paths have been removed; notebooks are **self‑contained**.
- Randomness is made reproducible with `set.seed()` in each notebook.
- If you want to publish rendered HTML with **GitHub Pages**, knit outputs to a `docs/` folder and enable Pages in repo settings.

## License
If needed for class sharing, you can add a permissive license (e.g., MIT).
