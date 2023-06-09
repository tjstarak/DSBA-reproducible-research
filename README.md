# Reproducible Research DSBA 2022/23 Summer semester

This project aims to reproduce parts of the paper ["Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone"](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5) by Davide Chicco and Giuseppe Jurman. The original paper uses R, we reproduce the results using Python.


## Organization

The work is split into three parts, each with its own Jupyter notebook:
1. Descriptive statistics and univariate analysis ([notebooks/01_descriptive_stats.ipynb](https://github.com/tjstarak/DSBA-reproducible-research/blob/main/notebooks/01_descriptive_stats.ipynb)) </br>
   Here, general descriptive statistics and univariate analysis are reproduced. 
2. Random forest ([notebooks/02_random_forest.ipynb](https://github.com/tjstarak/DSBA-reproducible-research/blob/main/notebooks/02_random_forest.ipynb))</br>
   Here, Random Forest reproduces the binary classification and their feature importance. 
3. Logistic regression ([notebooks/03_logistic_regression.ipynb](https://github.com/tjstarak/DSBA-reproducible-research/blob/main/notebooks/03_logistic_regression.ipynb))</br>
   Here, the unrestricted and restricted Logistic Regression results are reproduced.


## Data

We use the [dataset with medical records of 299 patients with heart failure](https://plos.figshare.com/articles/dataset/Survival_analysis_of_heart_failure_patients_A_case_study/5227684/1), published by Ahmad T, Munir A et al. alongside "Survival analysis of heart failure patients: a case study" in PLoS ONE. 


## Requirements

Reproducing our work requires Python and packages specified in `environment.yml`. To recreate the Conda environment run for example:
`conda create -f environment.yml`


## Team members
- Dustin Pacholleck
- Khon Nguyen
- Tomasz Starakiewicz
