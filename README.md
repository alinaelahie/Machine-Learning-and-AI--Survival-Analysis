# Machine-Learning-and-AI--Survival-Analysis
<h1>Overview
### Regular Text
<h3>This project focuses on survival analysis using the Head and Neck Cancer dataset sourced from The Cancer Imaging Archive. The dataset includes clinical information on patients diagnosed with head and neck cancer, with various features such as age, treatment modality, tumor stage, survival time, and event status (dead or alive).

<h3>The main goal of this analysis is to explore the factors influencing survival outcomes and to apply various statistical techniques, including Kaplan-Meier survival curves, Cox Proportional Hazards model, and Random Survival Forest (RSF). These methods are used to investigate the clinical significance of factors like age, treatment type, and stage of the disease.

<h1>Files and Directories
<h3>scripts/: Directory containing the Jupyter notebook (main.ipynb) used for survival analysis.
<h3>data/: Directory containing the dataset used in the analysis.

<h1>Installation and Requirements
<h2>Clone the repository to your local machine:

<h3>git clone https://github.com/alinaelahie/Machine-Learning-and-AI--Survival-Analysis.git

<h2>Install the required libraries:

<h3>pip install -r requirements.txt

<h1>Key dependencies include:

<h3>lifelines: For survival analysis and Cox Proportional Hazards model.

<h3>matplotlib, seaborn: For plotting Kaplan-Meier curves and other visualizations.

<h3>scikit-learn: For Random Survival Forest and other machine learning methods.

<h3>pandas: For data manipulation and analysis.

<h1>Methods
  
<h2>Kaplan-Meier Survival Curves
<h3>The Kaplan-Meier estimator is used to estimate the survival function and compare the survival distributions of different groups (e.g., Radiation vs. Chemotherapy, Age < 60 vs. ≥ 60). Log-rank tests are performed to test if survival curves differ significantly between groups.

<h2>Cox Proportional Hazards Regression
<h3>The Cox Proportional Hazards model is applied to identify the relationship between covariates (e.g., Age, Treatment Modality, and Stage) and survival time. Hazard ratios, p-values, and confidence intervals are provided to interpret the significance of each covariate.

<h2>Random Survival Forest
<h3>Random Survival Forest (RSF) is used to assess feature importance and predict survival outcomes. The C-Index is calculated to evaluate the predictive accuracy of the model.

