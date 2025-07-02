# 📊 Customer Churn Analysis & Prediction

A machine learning project to analyze customer churn data and predict which customers are likely to leave a telecom company. This project uses Python, Pandas, and Scikit-learn for data preprocessing, exploration, visualization, and predictive modeling.

---

## 🧠 Project Overview

Customer churn is a key business metric in the telecom industry. By predicting which customers are likely to churn, businesses can proactively take steps to retain them. This project follows a full data science workflow:

* Data Loading & Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training & Evaluation
* Accuracy and Confusion Matrix Reporting

---

## 📁 Project Structure

```
Customer-Churn-Analysis-Prediction/
│
├── data/                      # Dataset files (CSV, XLSX, etc.)
├── images/                    # Graphs and plots for EDA
├── notebooks/                 # Jupyter notebooks (optional)
├── models/                    # Saved ML models (if any)
├── churn_analysis.py          # Main Python script
├── requirements.txt           # Python dependencies
└── README.md                  # This file
```

---

## 🛆 Dependencies

Install the required packages using:

```bash
pip install -r requirements.txt
```

Main libraries used:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

---

## 🧹 Data Preprocessing

* Handled missing values in `TotalCharges`
* Converted categorical columns using label encoding or one-hot encoding
* Scaled numerical features for ML algorithms

---

## 📈 Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest
* Support Vector Machines (SVM)
* Accuracy comparison among models

---

## 🎯 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

---

## 📊 Example Output

```
Model Accuracy: 0.82
```

Confusion Matrix and classification report are displayed using matplotlib and sklearn's metrics.

---

## 💡 Future Improvements

* Use XGBoost or LightGBM for better accuracy
* Integrate with a web app (e.g., Flask or Streamlit)
* Automate with a dashboard for real-time churn prediction

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! Feel free to fork this repo and submit a pull request.

---

## ✍️ Author

**Ayush Soni**
📧 [gabru@gmail.com](mailto:soniayush3425@gmail.com)
🔗 [GitHub Profile](https://github.com/AyushSoni345)
