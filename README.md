# EPD-ML-Data-Quality-Assessment
Python code and Jupyter notebooks for machine learning modeling on large-scale Environmental Product Declaration (EPD) datasets, used to assess how EPD data quality affects global warming potential (GWP) prediction performance.

## Overview

This repository implements the full ML workflow used in the associated research article-"Quantifying the Impact of Data Quality on Machine Learning Prediction : A Large-Scale Study of Construction Product Environmental Declarations".
## Usage

Open the notebooks in Jupyter (Lab or Notebook) and run them in order, or use them independently. 

1. `Scenario_A_uncleaned_Version.ipynb` – Scenario A experiments.  
2. `Scenario_B_Cleaned_Version.ipynb` – Scenario B experiments.  
3. `Scenario_C_fined_tune_model[_updated].ipynb` – Scenario C experiments (tuned models and external validation).  

Adjust input/output paths inside the notebooks to match your local directory structure. 

## Data

The original EPD dataset used in the study is commercial data accessed via the ECO Platform network using API and cannot be redistributed in this repository. Users who wish to reproduce the analysis should obtain similar EPD data directly from ECO Platform under the platform’s terms and conditions.

The notebooks and code can be used with other EPD-like datasets by adapting file paths and field names.

## Code availability and citation

If you use this code in academic work, please cite the associated article:

> To be added after paper publication

You can cite the repository directly, for example:

> Bishwash Neupane (2026). *EPD-ML-DataQuality: Code for data quality assessment and ML modelling with EPD datasets*. GitHub repository, [https://github.com/<b2neupane>/<your-repo>](https://github.com/b2neupane/EPD-ML-Data-Quality-Assessment).
