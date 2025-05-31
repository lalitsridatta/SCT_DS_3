# SCT_DS_3
📊 Decision Tree Classifier: Bank Marketing Dataset
This project is part of my internship at Skill Craft Technology, where I applied machine learning techniques to predict customer responses to a marketing campaign using the Bank Marketing dataset from the UCI Machine Learning Repository.

🚀 Objective
To build a Decision Tree Classifier that predicts whether a customer will subscribe to a term deposit (yes or no) based on their demographic and behavioral data.

📁 Dataset
Source: UCI Machine Learning Repository

File: bank-full.csv

Separator: ;

The dataset includes features such as age, job, marital status, education, contact, campaign, and previous outcomes.

🔧 Tools & Libraries Used
Python 🐍

Pandas

NumPy

Matplotlib & Seaborn

scikit-learn

Jupyter Notebook

🧠 Key Steps
Data Preprocessing

Categorical variables were encoded using LabelEncoder.

Data was cleaned and structured for model training.

Model Training

Used DecisionTreeClassifier from sklearn.

Criterion used: entropy for information gain.

Model Evaluation

Evaluated using accuracy score, confusion matrix, and classification report.

Visualized decision boundaries using plot_tree.

📈 Results
The model effectively predicted customer responses.

Key insights were visualized using heatmaps and decision trees.
