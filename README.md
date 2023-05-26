# Reproducible Research, DSBA 2022/23 Winter

In this repo, we reproduce the main results of the paper by Davide Chicco and Giuseppe Jurman, "Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone", BMC Medical Informatics and Decision Making 20, 16 (2020). https://doi.org/10.1186/s12911-020-1023-5. The original paper is using R, we reproduce the results using Python.


## Organization

The work is split into three parts, each with its own Jupyter notebook:
1. Descriptive statistics and univariate analysis (notebooks/01_descriptive_stats.ipynb)
2. Random forest (notebooks/02_random_forest.ipynb)
3. Logistic regression (notebooks/03_logistic_regression.ipynb)


## Data

We use the dataset with medical records of 299 patients with heart failure, published by Ahmad T, Munir A, et al. alongside "Survival analysis of heart failure patients: a case study" in PLoS ONE and available under https://plos.figshare.com/articles/dataset/Survival_analysis_of_heart_failure_patients_A_case_study/5227684/1


## Requirements

Reproducing our work requires Python and packages specified in `environment.yml`. To recreate the Conda environment run:
`conda create -f environment.yml`


## Team members
- Dustin Pacholleck
- Khon Nguyen
- Tomasz Starakiewicz
