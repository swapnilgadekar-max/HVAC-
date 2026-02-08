# HVAC-
# HVAC Energy Consumption Prediction

## 📌 Project Overview
This project focuses on predicting **energy consumption of HVAC systems** using machine learning.  
By leveraging environmental and operational parameters, the model helps in understanding and optimizing energy usage in smart buildings.

The solution is designed as a **hackathon-ready baseline**, emphasizing clarity, reproducibility, and practical impact.

---

##  Objective
- Predict HVAC **energy consumption** based on input features
- Reduce unnecessary energy usage
- Provide insights for **energy-efficient building management**

---

## 🧠 Approach
We treat this as a **regression problem**, where the target variable is continuous energy consumption.

### Steps Followed:
1. Load and inspect dataset  
2. Handle missing values  
3. Split data into training and testing sets  
4. Apply feature scaling  
5. Train a **Random Forest Regressor**  
6. Evaluate using regression metrics  

---

## 🗂 Dataset
The dataset includes parameters such as:
- Temperature
- Humidity
- Occupancy
- Energy Consumption (Target)

> Note: Column names may vary depending on the dataset source.

---

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn

---

## 📊 Model Used
**Random Forest Regressor**

Chosen because:
- Handles non-linear relationships well
- Robust to noise
- Performs strongly with minimal tuning

---

##  Evaluation Metrics
Since this is a regression problem, we use:

- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

These metrics help quantify prediction accuracy and model reliability.

---

## 📊 Results Summary

The model demonstrates strong predictive performance on the test dataset.

| Metric | Value |
|------|------|
| MAE (Mean Absolute Error) | 2276.28 |
| RMSE (Root Mean Squared Error) | 3408.00 |
| R² Score | 0.9775 |

### Interpretation
- **Low MAE** indicates minimal average prediction error.
- **RMSE** highlights the model’s robustness against large deviations.
- **High R² Score (0.97+)** shows the model explains most of the variance in HVAC energy consumption.

Overall, the results confirm that the model is highly effective for estimating energy usage in HVAC systems.
---
##  How to Run the Project

1. Clone the repository
```bash
git clone <repository-url>
cd <project-folder>

2. Install Dependices 
```bash
pip install pandas numpy scikit-learn 

3.  Run the script
```bash 
python main.py
