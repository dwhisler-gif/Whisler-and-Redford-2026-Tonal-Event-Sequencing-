# Analysis

This folder contains scripts, notebooks, and analysis workflows used to process and evaluate project data.

## Suggested structure

- `scripts/` — reproducible analysis scripts
- `notebooks/` — exploratory or explanatory notebooks
- `reports/` — summary output and generated reports

## Current analysis archive

`dataAnalysesR_tonalEventSequencing` is the main analysis source archive. The repository contains Matrix, TBW, and Discrimination age-group workbooks, Gorilla ZIP exports, a demographic workbook, and the Segmentation and Stimulus Validation materials under `data/spreadsheets/`. These materials are distinct from the following inputs referenced by the analysis source, which are absent: `gorilla_export.csv`, `Temporal Order Judgement.xlsx`, `Predictor File.xlsx`, `Matrix Task.xlsx`, and `TBW Measure.xlsx`. Do not assume the archived materials are equivalent substitutes; analysis sections that require the missing inputs cannot be reproduced from the repository contents alone. Run repository-relative paths from the repository root.

Some references use machine-specific absolute paths, which must be adapted locally before those sections can run.

The source loads and installs a number of R packages, but the full dependency set and versions have not been verified. Record the R version and package versions in a reproducible environment specification when the analysis workflow and its required inputs are validated. Generated outputs are currently written to the working directory in several script sections; review output paths before running analyses.
