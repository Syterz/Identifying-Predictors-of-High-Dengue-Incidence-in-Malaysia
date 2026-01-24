# Identifying Predictors of High Dengue Incidence in Malaysia 

Short description
This repository contains materials for a project investigating whether short-term engineered weather signals (temperature, precipitation, humidity, windspeed) improve early detection of dengue surges in Malaysia. The work uses weekly dengue surveillance (2011–2024) from the Open Dengue Project and MoH portal’s database, and weather from the NASA POWER API and evaluates XGBClassifier models with explainability (SHAP), permutation importance and ablation testing.

What’s here
- `Executive Summary.pdf` - one-page executive summary of the project and main results.
- `notebooks/01_analysis_overview.ipynb` - cleaned notebook demonstrating the analysis workflow. Original data are not included.
- `DATA_INSTRUCTIONS.md` - instructions to download the public datasets used in this study.
- `requirements.txt` - packages and versions.

Important note about data
The original dengue and weather datasets used in the analysis are **not** included for privacy and size reasons. See `DATA_INSTRUCTIONS.md` for download links and steps to reproduce the analysis.
