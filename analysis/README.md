# Analysis

This folder contains scripts, notebooks, and analysis workflows used to process and evaluate project data.

## Suggested structure

- `scripts/` — reproducible analysis scripts
- `notebooks/` — exploratory or explanatory notebooks
- `reports/` — summary output and generated reports

## Current analysis archive

`dataAnalysesR_tonalEventSequencing` is the main analysis source archive. It reads archived Matrix, TBW, and Discrimination workbooks from `data/spreadsheets/`, the segmentation workbook from `data/spreadsheets/Segmentation/`, and stimulus validation data from `data/spreadsheets/Stimulus Validation/`. Run repository-relative paths from the repository root.

The script also refers to inputs that are not currently in this repository, including `gorilla_export.csv`, `Temporal Order Judgement.xlsx`, `Predictor File.xlsx`, `Matrix Task.xlsx`, and `TBW Measure.xlsx`; some references use machine-specific absolute paths. Those sections will need the corresponding authorized inputs and locally adapted paths before they can run.

The source loads and installs a number of R packages, but the full dependency set and versions have not been verified. Record the R version and package versions in a reproducible environment specification when the analysis workflow and its required inputs are validated. Generated outputs are currently written to the working directory in several script sections; review output paths before running analyses.
