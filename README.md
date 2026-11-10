# Tonal Event Sequencing

This repository contains experimental materials, analysis scripts, and documentation associated with the Tonal Event Sequencing project.

It is organized as a versioned project archive. The current contents do not by themselves guarantee that every analysis can be reproduced: some scripts refer to input files stored outside this repository.

## Purpose

This project is designed to host:
- experimental stimuli and task materials
- analysis code and notebooks
- processed or de-identified data
- documentation of procedures and methods
- figures, tables, and supplementary outputs
- publication-ready project metadata

## Repository structure

- `data/` — data files, codebooks, and documentation; `data/spreadsheets/` contains the archived spreadsheets and ZIP files previously in `RR-Raw Data/`, the Segmentation and Stimulus Validation materials, and the demographic workbook
- `stimuli/` — stimulus files, task materials, and presentation assets
- `analysis/` — scripts, notebooks, and processing pipelines
- `results/` — generated figures, tables, and summary outputs
- `docs/` — methodological documentation and project notes
- `README.md` — project overview and usage information
- `CITATION.cff` — citation metadata for the project
- `LICENSE` — repository license

## Recommended use

This repository can serve as a record of the project lifecycle, including:
- study materials and implementations
- data processing steps
- analysis reproducibility
- documentation for manuscript preparation

## Data and materials guidance

Please follow these norms when adding content:
- avoid including personally identifiable information
- confirm consent, sharing permissions, and applicable ethics requirements before publishing participant-level data; do not assume files are safe to share because they are in this repository
- document file naming conventions and variable definitions
- store large files using Git LFS or institutional archival storage, if needed
- clearly label raw, processed, and final stages of the data

## Reproducibility

Run repository-relative script paths from the repository root. Several analyses also use external inputs not currently included here, including `gorilla_export.csv`, `Temporal Order Judgement.xlsx`, `Predictor File.xlsx`, `Matrix Task.xlsx`, and `TBW Measure.xlsx`. The analysis script also installs or loads R packages; a complete, verified dependency specification has not yet been established. See `analysis/README.md` for details.

## Citation

Please cite this repository using the metadata in `CITATION.cff` or via the project DOI/reference once available.

## License

This project is distributed under the MIT License. See `LICENSE` for details.

## Contact

For questions regarding data availability, methods, or project materials, please contact the project authors or maintainers.
