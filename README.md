🚨 Fraud Detection Using Machine Learning
📌 Project Overview

This project builds a machine learning model to detect fraudulent financial transactions using a highly imbalanced dataset of 6.3 million rows.

The goal is to accurately detect fraud while minimizing false positives.

📊 Dataset

Total Rows: 6,362,620

Features: 11

Fraud cases: ~0.13% (Highly Imbalanced)

🧠 Model Used

Random Forest Classifier

Class weight balancing for imbalanced data

Parallel processing (n_jobs=-1) for faster training

⚡ Performance (Full Dataset)

Training Time: 257 seconds

Metric	Normal	Fraud
Precision	1.00	0.98
Recall	1.00	0.78
F1-score	1.00	0.87

Confusion Matrix:

[[1270858      23]
 [    368    1275]]

🔍 Key Achievements

✔ Successfully trained on 6.3M rows
✔ Achieved 98% fraud precision
✔ Maintained low false positives
✔ Optimized training using parallel CPU processing
✔ Reduced training time significantly

🚀 Future Improvements

Implement XGBoost / LightGBM for better recall

Apply SMOTE for better fraud detection

Hyperparameter tuning using GridSearchCV

Threshold optimization for better fraud capture

Deploy as a Flask API

Create Streamlit dashboard

🛠 Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

📈 Why This Project Matters

Fraud detection is a real-world industry problem used in banking, fintech, and cybersecurity.

This project demonstrates handling:

Large-scale datasets

Imbalanced classification

Performance optimization

Model evaluation
