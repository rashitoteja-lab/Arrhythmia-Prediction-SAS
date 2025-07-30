###🫀 Heart Arrhythmia Prediction (SAS)


📌 Project Overview
This project predicts heart arrhythmia using the UCI Heart Arrhythmia dataset with SAS for data preprocessing, modeling, and evaluation. It uses multiple ML algorithms, feature selection, and model comparison.

🔧 Tech Stack
SAS OnDemand / SAS Studio

GitHub (for version control and portfolio)

📂 Project Structure

kotlin

Copy

Edit
📁 Heart-Arrhythmia-Prediction

│── data/

│   └── heart_arrhythmia.csv

│── sas_code/

│   ├── preprocessing.sas

│   ├── modeling.sas

│   ├── evaluation.sas

│── outputs/

│   ├── predictions.csv

│   ├── roc_points.csv

│   ├── feature_importance.csv

│── README.md

🚀 Steps Performed

1️⃣ Data Preprocessing

Imported dataset with PROC IMPORT

Handled missing values using PROC MI

Normalized and standardized features

Encoded categorical variables

2️⃣ Feature Selection & EDA

Used PROC HPREDUCE and PROC VARCLUS for variable reduction

Visualized data using SGPLOT and SGSCATTER

3️⃣ Modeling

Logistic Regression with PROC HPLOGISTIC

Decision Trees & Random Forest with PROC HPFOREST

Neural Network with PROC HPNEURAL

Applied k-fold cross-validation macros

4️⃣ Evaluation

Confusion matrix generation

ROC curves & AUC calculation

Feature importance ranking

5️⃣ Exporting Outputs
Model predictions (predictions.csv)

ROC curve points (roc_points.csv)

Feature importance scores (feature_importance.csv)

📈 Results

Multiple models trained and compared using AUC and accuracy

Identified key ECG features contributing to arrhythmia classification

📌 How to Run

Clone the repository.

Open .sas scripts in SAS OnDemand/SAS Studio.

Update file paths for your environment.

Run scripts in the order:

preprocessing.sas

modeling.sas

evaluation.sas

Check outputs/ folder for generated CSVs.

