# British Airways Forage Job Sim Project

This project uses a machine learning approach to **predict whether a customer will make a flight booking**, based on various travel-related features. It includes full data exploration, feature engineering, model training, evaluation, and business-level insights.

---

## 🔍 Overview

### ✅ Goal
To develop a predictive model that estimates the likelihood of a customer making a booking, allowing for better customer targeting and operational insights.

### ✅ Dataset
A flight-related dataset (not included here) that includes customer behavior, booking dates, route information, and other relevant attributes.

---

## 🧪 Workflow

1. **Data Exploration & Cleaning**
   - Checked data types, null values, and basic statistics
   - One-hot encoding of categorical variables

2. **Feature Engineering**
   - Created new features to enhance predictive power (e.g., `days_until_flight`, `is_weekend`)
   - Removed irrelevant columns

3. **Model Training**
   - Trained a `RandomForestClassifier`
   - Used `train_test_split` and `cross_val_score` for evaluation

4. **Evaluation**
   - Output metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix and classification report included

5. **Interpretation**
   - Visualized top features contributing to predictions
   - Identified key behavioral drivers behind bookings

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Getting_Started_Modified.ipynb` | Jupyter Notebook with complete data processing, model training, and evaluation |
| `Booking_Model_Summary_Slide.pptx` | One-slide executive summary with results and recommendations |
| `README.md` | This project description |

---

## 📈 Results (Example)

- **Cross-validation Accuracy**: ~`XX%` (fill in your value)
- **Top Features**:
  - `days_until_flight`
  - `fare_type`
  - `booking_time_of_day`
  - `route_region`
  - `loyalty_status`

---

## 📌 How to Run

1. Clone this repo or download the files
2. Replace `"your_dataset.csv"` in the notebook with your actual dataset
3. Open `Getting_Started_Modified.ipynb` in JupyterLab or VS Code
4. Run all cells to reproduce the model training and insights

---

## 🚀 Future Improvements

- Hyperparameter tuning for Random Forest
- Experiment with XGBoost or GradientBoosting
- Deploy model with Flask or Streamlit for live inference
- Connect to real-time booking database

---

## 📧 Contact

If you'd like to collaborate or have questions, feel free to reach out!

---

