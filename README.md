# Task 6: House Price Prediction

## 🎯 Objective
To build a regression model that predicts house prices based on square footage, number of bedrooms, and location-related features using the Boston Housing dataset.

---

## 📊 Dataset Used
- **Name:** Boston Housing Dataset
- **Source:** [UCI Repository via GitHub](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)
- **Size:** 506 rows × 14 columns
- **Target Variable:** `medv` (Median value of owner-occupied homes in $1000s)

---

## 📌 Features Used
| Feature | Description |
|---------|-------------|
| `rm`    | Average number of rooms per dwelling (used as square footage proxy) |
| `dis`   | Weighted distance to five Boston employment centers (location-related) |
| `rad`   | Index of accessibility to radial highways (location accessibility) |

---

## ⚙️ Models Applied
- **Linear Regression** using `scikit-learn`

---

## 📈 Key Results and Findings
- **Mean Absolute Error (MAE):** Shows the average dollar deviation between predicted and actual prices
- **Root Mean Squared Error (RMSE):** Penalizes larger errors and reflects prediction accuracy
- **Scatter Plot:** Shows a good overall trend between predicted and actual house prices

---

## 🧠 Final Insights
- The Linear Regression model performs reasonably well with basic features.
- Features related to size (`rm`) and location (`dis`, `rad`) have visible influence on prices.
- Prediction accuracy can be improved by including more relevant features or using advanced models like Gradient Boosting.

---

## 📁 Files Included
- `Task6_House_Price_Prediction.ipynb`: Notebook with code, plots, and explanations
- Dataset loaded directly from a public URL (no upload needed)
