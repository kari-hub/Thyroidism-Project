# Hypothyroidism-Project
## Overview 

Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients. The goal is to build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroidism.

### Carry out Exploratory Data Analysis.

### Part 1: Decision trees:
- For this section, we are building a model that makes the above prediction without using individual decision trees. The models tested in this project are Random forests, Ada-boosted trees and gradient-boosted trees.

### Part 2: SVM:

- Applied Polynomial, linear and rbf kernel functions to build our SVM model and then evaluated their performance and picked the kernel that performed best. 

-  After getting the best-performing kernel, we used this kernel together with our tuned parameters and repeated prediction but this time using additional features.  

### Dataset Columns

Age,
Sex,
on_thyroxine,
query_on_thyroxine,
on_antithyroid_medicationthyroid_surgery,
query_hypothyroid,
query_hyperthyroid,
pregnant,
sick,
tumour,
lithium,
goitre,
TSH_measured,
TSH,
T3_measured,
T3,
TT4_measured,
TT4.
