# medical-cost-classification
## Project Overview
This repository contains a supervised learning project focused on building classification pipelines to predict insurance risk categories. Using the Medical Cost Personal Dataset, the project transforms continuous financial medical charges into a binary classification problem: identifying individuals as **High Cost** vs. **Low Cost** based on demographic and lifestyle indicators.

## Dataset
* **Source:** Kaggle Medical Cost Personal Dataset
* **Features Used:** Age, Sex, BMI, Children, Smoking Status, Region
* **Target Variable:** `cost_class` (0 = Low Cost, 1 = High Cost based on median split)

## Key Technical Workflows
* **Data Preprocessing:** Handled missing data, eliminated duplicates, performed Label Encoding on categorical variables, and applied Standard Scaling.
* **Exploratory Data Analysis (EDA):** Visualized class distributions and established feature correlation matrices.
* **Model Implementation:** Evaluated and compared **Logistic Regression** and **Decision Tree Classifier** frameworks.
* **Interpretation:** Generated confusion matrices and ROC-AUC curves to assess predictive strength.

## How to Run the Notebook
1. Open the `.ipynb` file within this repository.
2. Click the **Open in Colab** badge at the top of the file (once linked).
3. Ensure you run the code blocks sequentially from top to bottom. The notebook automatically fetches the dataset directly from the cloud—no manual local file downloads are required.
