<img src="https://github.com/Mordechai2024/Mushroom-Classification-Project/blob/main/Mushrooms%20image.jpg?raw=true" alt="Example Image" width="900" height="400" style="float: right; margin-right: 10px;"/>

# Mushroom Classification Project
This project focuses on building a machine learning model that predicts whether mushrooms are edible or poisonous based on their physical characteristics. The dataset used for this task is derived from the well-known UCI Mushroom dataset.

# Key Aspects:
Dataset: The training dataset contains various features of mushrooms, such as cap shape, color, and bruising. The goal is to classify each mushroom as either edible ('e') or poisonous ('p') based on these features.

# Techniques Used:
Exploratory Data Analysis (EDA) to understand the distribution and correlation of features.

# Modeling: 
Several models were evaluated, including Logistic Regression, Decision Trees, Random Forest, and XGBoost.

# Evaluation: 
The performance was assessed using metrics such as ROC-AUC, accuracy,Recall and confusion matrices, with a focus on minimizing false negatives to ensure poisonous mushrooms are accurately identified.
The notebook includes data preprocessing steps like OneHotEncoding, model comparison using GridSearchCV, and visualizations like the ROC curve and confusion matrix.
