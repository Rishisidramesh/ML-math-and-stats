📊 ML Math & Statistics Learning (Version 1 – In Progress)

🚀 Overview

This repository is a work-in-progress learning log where I am building my foundation in Mathematics and Statistics for Machine Learning using Python and real datasets (Titanic).

The focus is on:

Learning concepts → Implementing in code → Understanding data behavior

This is NOT a completed project, but a structured learning journey.

🎯 Current Goal
Build strong intuition in statistics for ML
Learn how data behaves using visualization
Apply math concepts using Python
Gradually move toward ML model building

📚 Topics Currently Being Learned

🟡 Statistics (In Progress)
Histogram interpretation
Mean, Median, Mode
Variance and Standard Deviation
Data distribution (skewness, shape)
Outlier intuition (basic)

🟡 Data Exploration (EDA – Early Stage)
Titanic dataset exploration
Understanding survival patterns
Group-based analysis (Survived vs Age)

🧠 Key Learnings So Far
Histograms help understand data distribution visually
Mean and median behave differently in skewed data
Variance describes how spread out the data is
Age alone is not a strong predictor of survival in Titanic dataset
Visualization is essential for statistical understanding

🛠️ Tools Used
Python 🐍
NumPy
Pandas
Matplotlib
SciPy
Jupyter Notebook
📂 Project Structure
ML-math-and-stats/
│
├── implement_central_tendency.ipynb   # Main learning notebook
├── train_and_test2.csv                # Titanic dataset
├── notes.docx                         # Personal learning notes
├── .gitignore                         # Ignored system/environment files
└── README.md                          # Project documentation

🔍 Current Analysis Example
df.groupby("Survived")["Age"].mean()

👉 Shows slight difference in average age between survivors and non-survivors

📊 Important Observation
Age distribution is slightly right-skewed
Difference in survival based on age is small
Feature importance is not yet finalized (more analysis needed)
🚧 What is NOT Done Yet (Important)

This project is still in early stage:

❌ No ML models built yet
❌ No feature engineering completed
❌ No predictions or evaluation done
❌ No preprocessing pipeline yet
🚀 Next Steps
Deeper variance & standard deviation analysis
Outlier detection techniques
Feature engineering on Titanic dataset
First ML model (Logistic Regression)
Model evaluation metrics (accuracy, precision, recall)
📌 Status

🟡 Version 1 — Learning & Exploration Phase (Ongoing)

👨‍💻 Author

Rishi Musti
Data Science Student | Learning Machine Learning Step-by-Step