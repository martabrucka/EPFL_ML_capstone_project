# EPFL_ML_capstone_project

The problem I address in this project is a differentation between patients in different stages after the COVID-19 infection,
based on the quantities of metabolites and other substances present in the blood samples of these patients. 
The amount of metabolites, lipids (and other substances) can be seen as a fingerprint of the health condition of a patient. 
There are three groups of patients represented in the dataset: 
"i) hospitalized COVID-19 positive patients (=<21 days from the first positive nasopharyngeal swab, acute phase COVID); 
ii) hospitalized COVID-19 positive patients (>21 days from the first positive nasopharyngeal swab, post-acute phase COVID); 
iii) subjects after 2–6 months from SARS-CoV-2 eradication post COVID." ([ref1]). 
The objective is to check whether the three groups of subjects are distinct enough (in terms of their metabolomic and lipidomic profile) 
so that a model could be built to predict the three classes. 
Alternatively, if only the two most extreme classses (acute phase COVID and post-COVID) are distinguishable, 
a model that will be built for the binary classification could be further used to predict the condition of the subjects from the third group (post-acute phase COVID). 
The importance of features provided by the different models that will be compared in this project may give insights 
into how metabolomic/lipidomic profiles change in subjects accross the different stages after COVID-19 infection.

[ref1] https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1010443

The entire project is split into separate notebooks that should be executed in a sequence: c5_01, c5_02 etc. 
The respective files contain: 

c5_01: reading the dataset and basic exploratory data analysis (EDA)

c5_02: dimensionality reduction with PCA

c5_03: In-depth Exploratory data analysis (EDA)

c5_04: Logistic regression model

c5_05: Random forest model

c5_06: k-Nearest Neighbours model

c5_07: Comparison of the models



