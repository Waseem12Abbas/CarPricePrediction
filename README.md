# 🚗 Car Price Prediction Using Machine Learning

This project predicts the selling price of used cars based on features like mileage, present price, fuel type, year, transmission, and ownership. It demonstrates the end-to-end workflow of a supervised regression problem using real-world automobile data.

---

## 📂 Dataset

- Source: [Used Cars Dataset on Kaggle](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)
- Contains data on various car models, their specifications, and selling prices.

---

## 📊 Project Workflow

### ✅ Step 1: Data Preprocessing
- Handled missing values and duplicates
- Converted string-based numeric columns like `Driven_kms` into proper numeric format
- Converted categorical variables (`Fuel_Type`, `Transmission`, etc.) using one-hot encoding

### ✅ Step 2: Exploratory Data Analysis (EDA)
- Visualized distributions of price and mileage
- Analyzed relationships between price and features using scatter plots and boxplots
- Generated a correlation heatmap for numeric features

### ✅ Step 3: Model Building
- Split data into training and testing sets (80/20)
- Scaled features using `StandardScaler` for linear regression
- Trained and compared:
  - 🔹 Linear Regression
  - 🌲 Random Forest Regressor

### ✅ Step 4: Evaluation
- Metrics used:
  - **R² Score**: Coefficient of determination
  - **Mean Squared Error (MSE)**
- Visualizations:
  - Actual vs Predicted Price Plot (Linear Regression)
  - Feature Importance Bar Chart (Random Forest)

---

## 📈 Results

| Model                | R² Score | MSE (approx) |
|---------------------|----------|--------------|
| Linear Regression    | ~0.85    | Varies       |
| Random Forest        | ~0.92    | Lower        |

> Random Forest outperformed Linear Regression, especially in handling nonlinear relationships and complex feature interactions.

---

## 🛠️ Tools & Technologies

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (LinearRegression, RandomForestRegressor, metrics)
- Jupyter Notebook

---

## 🎥 LinkedIn Demo

📽 [Watch the Project Walkthrough Video on LinkedIn](#your-link-here)  
*Don't forget to tag [@CodeAlpha](https://www.linkedin.com/company/codealpha-internships/) in your post!*

---

## 📤 Submission

✅ Submitted as part of the **CodeAlpha Data Science Internship**  
📅 Completed in: June 2025  
👤 By: Waseem Abbas

---

## 📎 Repository Structure

📁 CarPricePrediction
├── Car_Price_Prediction.ipynb ← main notebook
├── README.md ← this file



---

## 🙌 Acknowledgements

Thanks to **CodeAlpha** for the opportunity and guidance during this internship.  
Dataset credits: Kaggle contributor [vijayaadithyanvg](https://www.kaggle.com/datasets/vijayaadithyanvg)


 
