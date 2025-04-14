# DIGIBHEM

# 💳 Credit Card Fraud Detection using Machine Learning

This project is a complete pipeline for detecting fraudulent transactions using a supervised machine learning approach. The dataset used is highly imbalanced, and techniques like SMOTE and StandardScaler are employed to improve model performance.

# 📌 Table of Contents

o About the Project

o Technologies Used

o Data Preprocessing

o Model Training

o Evaluation Metrics

o User Interface

o How to Run

o Results

o Conclusion

# 📖 About the Project

Credit card fraud causes billions of dollars in losses annually. This project aims to develop a machine learning-based solution that can detect fraudulent transactions from anonymized transaction data using classification algorithms.

# ⚙️ Technologies Used

o Python 🐍

o NumPy & Pandas (Data handling)

o Matplotlib & Seaborn (Visualization)

o Scikit-learn (Modeling & Evaluation)

o imbalanced-learn (SMOTE)

o Jupyter Notebook

# 🔍 Data Preprocessing
1. Load Dataset
   Reads the creditcard.csv file into a DataFrame.

2. Handle Imbalanced Data
   Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes.

3. Feature Scaling
   Scaled features using StandardScaler to normalize data and enhance model performance.

# 🧠 Model Training
  Two machine learning models were trained and compared:

1. ✅ Random Forest Classifier

2. 🌲 Gradient Boosting Classifier

   A stratified split was used to maintain the distribution of classes during training/testing.

# 📊 Evaluation Metrics
  The models were evaluated using:

o Accuracy

o Precision

o Recall

o F1 Score

o Classification Report

  These metrics help measure how well the models perform especially in detecting rare fraudulent cases.

# 🧪 User Interface
  A simple command-line interface allows users to input transaction values and receive real-time fraud predictions.

# 🚀 How to Run
1. Clone this repository:
   
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection

2. Install dependencies:

pip install -r requirements.txt

3. Run the notebook:

jupyter notebook "credit card fraud detection.ipynb"

# 📈 Results
   The best performing model achieved high precision and recall, indicating that it is effective at identifying fraudulent transactions with minimal false positives.

# 🧾 Conclusion
  This project demonstrates the potential of machine learning in solving real-world problems like fraud detection. Techniques like SMOTE and ensemble classifiers provide robust results even with imbalanced datasets.

# 🙌 Acknowledgements
  Dataset from Kaggle Credit Card Fraud Detection

# Libraries: 
  scikit-learn, pandas, matplotlib, seaborn, imbalanced-learn
