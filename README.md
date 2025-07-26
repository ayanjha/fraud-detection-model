💸 Fraud Detection using Machine Learning

A machine learning model built to detect fraudulent financial transactions using a dataset of 6.3 million records. The project includes data preprocessing, class balancing using SMOTE, model training, evaluation, and final deployment using a pickled model.



📂 Dataset

Source: Synthetic financial transaction dataset



Records: 6,024,548



Features: Transaction type, amount, origin/destination balances, and fraud flags



Target Variable: isFraud (1 = fraud, 0 = normal transaction)



🧠 ML Workflow

Exploratory Data Analysis (EDA)

✔️ Checked for missing values

✔️ Analyzed class distribution

✔️ Detected imbalance in fraud vs non-fraud transactions



Data Preprocessing

✔️ Categorical encoding using pd.get\_dummies()

✔️ Feature scaling using StandardScaler

✔️ Class balancing using SMOTE



Model Training



Algorithms tried:

✅ Logistic Regression

✅ Random Forest

✅ XGBoost



Best performance: Random Forest



Evaluation Metrics



Precision, Recall, F1-Score



Confusion Matrix



ROC-AUC Score



Model Saving

✔️ Final model saved as fraud\_model.pkl using joblib



📈 Results

Achieved high recall and precision for fraud detection



Handled severe class imbalance using SMOTE



Robust evaluation for imbalanced classification



🚀 How to Run

Clone the repository



bash

Copy

Edit

git clone https://github.com/your-username/fraud-detection-model.git

cd fraud-detection-model

Install dependencies



nginx

Copy

Edit

pip install -r requirements.txt

Run the notebook

Open fraud\_detection.ipynb in Jupyter or Google Colab



🔧 Requirements

nginx

Copy

Edit

pandas

numpy

scikit-learn

imblearn

matplotlib

xgboost

joblib

📁 Files

File	Description

fraud\_detection.ipynb	Jupyter notebook with full pipeline

fraud\_model.pkl	Trained ML model (Random Forest)

README.md	Project documentation



📬 Contact

Made with ❤️ by Aryan Kumar

