# Hypothyroidism-Project

## Overview

This project analyzes data collected by Nairobi Hospital during a clinical camp focused on hypothyroidism testing. The dataset includes information on thyroid patients and aims to build a machine learning model that predicts whether a patient’s symptoms indicate hypothyroidism.

The objective is to apply various machine learning models and techniques to determine if the patient has hypothyroidism based on their medical data.

## Steps Involved

### 1. Exploratory Data Analysis (EDA)
Before building the models, we perform an Exploratory Data Analysis (EDA) to understand the dataset, visualize relationships between features, and check for missing or unusual data.

### 2. Part 1: Decision Trees
In this section, we build a predictive model using ensemble methods, rather than individual decision trees. We test the following models:
- **Random Forests**: An ensemble of decision trees for better accuracy.
- **AdaBoosted Trees**: A boosting technique that focuses on misclassified instances to improve model performance.
- **Gradient-Boosted Trees**: A boosting algorithm that optimizes the model by correcting errors in sequential stages.

### 3. Part 2: Support Vector Machines (SVM)
For this part, we apply Support Vector Machines (SVM) with three different kernel functions:
- **Polynomial Kernel**
- **Linear Kernel**
- **Radial Basis Function (RBF) Kernel**

We evaluate the performance of each kernel function and select the best-performing one. After selecting the best kernel, we fine-tune the model's hyperparameters and make predictions using additional features to further improve accuracy.

## Dataset Columns
The dataset contains the following columns that describe the patients' characteristics:

- **Age**: The age of the patient.
- **Sex**: Gender of the patient.
- **on_thyroxine**: Whether the patient is currently taking thyroxine medication.
- **query_on_thyroxine**: Whether the patient has ever inquired about thyroxine medication.
- **on_antithyroid_medication**: Whether the patient is on antithyroid medication.
- **thyroid_surgery**: Whether the patient has had thyroid surgery.
- **query_hypothyroid**: Whether the patient has inquired about hypothyroidism.
- **query_hyperthyroid**: Whether the patient has inquired about hyperthyroidism.
- **pregnant**: Whether the patient is pregnant.
- **sick**: Whether the patient is currently sick.
- **tumour**: Whether the patient has a tumor.
- **lithium**: Whether the patient is on lithium medication.
- **goitre**: Whether the patient has a goitre (enlarged thyroid).
- **TSH_measured**: Whether the patient's TSH (Thyroid Stimulating Hormone) levels were measured.
- **TSH**: The level of TSH in the patient's blood.
- **T3_measured**: Whether the patient's T3 levels were measured.
- **T3**: The level of T3 in the patient's blood.
- **TT4_measured**: Whether the patient's TT4 (Total T4) levels were measured.
- **TT4**: The level of TT4 in the patient's blood.

## Installation & Usage

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    ```

2. **Install required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the code**:
    - To perform exploratory data analysis, run the `eda.py` script.
    - To train the decision tree models, run `decision_trees.py`.
    - To implement the SVM model, run `svm_model.py`.

## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository, create a new branch, and submit a pull request.

### How to contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Conclusion

This project applies machine learning models to predict hypothyroidism from a range of medical features, exploring various machine learning techniques including ensemble decision trees and Support Vector Machines. The goal is to create an effective predictive model that could assist in diagnosing hypothyroidism based on patient data.
