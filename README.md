
# 🏠 House Price Prediction using Regression Models

This is **Task 4** of my Data Science Internship at DevelopersHub Corporation.

The goal of this project is to build regression models from scratch to **predict house prices** using the **California Housing Dataset**, and compare their performance.

---

## 📁 Dataset Used

I used the **California Housing Dataset** from Scikit-learn.  
👉 It contains information like house age, median income, number of rooms, and location-based features.

---

## 📘 Steps I Followed

### 1. Data Loading & Preprocessing
- Loaded the dataset using `fetch_california_housing()` from `sklearn.datasets`
- Normalized the numeric features using Min-Max scaling
- Split the data into training and testing sets

### 2. Data Visualization
- Created histogram for the target variable (house value)
- Plotted heatmap to see correlation between features
- Made scatterplot to show relation between income and price

### 3. Model Implementation
- Built **Linear Regression from scratch** using gradient descent
- Avoided using built-in models like `sklearn.linear_model.LinearRegression`
- Calculated predictions using weights and updated them manually

### 4. Model Evaluation
- Evaluated model performance using:
  - **RMSE (Root Mean Squared Error)**
  - **R² Score**

### 5. Sample Visuals
- All visuals are saved in the `images/` folder:
  - `target_distribution.png`
  - `correlation_heatmap.png`
  - `income_vs_price.png`

---

## 📦 Files in the Repository

```bash
House-Price-Prediction/
│
├── HousePricePrediction.ipynb       # Main notebook with code and output
├── images/                          # Folder for visualizations
│   ├── target_distribution.png
│   ├── correlation_heatmap.png
│   └── income_vs_price.png
├── house_data.csv (optional)        # For locally saved version of dataset
└── README.md                        # This file
```

---

## 🧪 How to Run This Project

You can run this notebook on:
- Jupyter Notebook on your system

### Required Libraries:
```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 🔗 Project Links

- 🧠 **Kaggle Notebook:** [https://www.kaggle.com/code/ashirzaki/house-price-prediction-californiadataset/edit]

---

## 📬 Contact

**Hashir**  


