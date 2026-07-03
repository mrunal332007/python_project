# python_project
it is a machine learning mini project 



# ⚽ Football Team Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the market value (Price) of football teams using Machine Learning. The dataset contains financial, performance, and attendance-related information about football clubs. Different regression models were trained and compared to identify the model that provides the best prediction performance.

---

## 🎯 Objective

The main objective of this project is to build a complete Machine Learning pipeline that can predict a football team's price based on various club-related features.

---

## 📂 Dataset Information

The dataset contains information such as:

* Team Price
* Total Revenue Last Season
* Average Attendance
* Transfer Spending Last Season
* Transfer Income Last Season
* Other team-related financial attributes

### Target Variable

**Price** (Football Team Market Value)

---

## 🛠️ Steps Performed

### 1. Data Loading

* Imported the dataset using Pandas.
* Checked dataset shape and structure.

### 2. Data Exploration

* Displayed first few rows.
* Viewed dataset information.
* Generated statistical summaries.
* Checked missing values and duplicate records.

### 3. Data Cleaning

* Removed duplicate rows.
* Converted the Price column into numeric format.

### 4. Feature Engineering

Created new features:

* **Revenue_Per_Attendance**

  Revenue generated per attendee.

* **NetTransferSpend**

  Transfer Spending − Transfer Income.

### 5. Exploratory Data Analysis (EDA)

Visualizations used:

* Histogram of team prices
* Boxplot for outlier detection
* Correlation Heatmap

### 6. Outlier Handling

* Used the IQR (Interquartile Range) method to remove extreme outliers from the target variable.

### 7. Data Preprocessing

* Applied One-Hot Encoding for categorical variables.
* Split data into training and testing sets.
* Standardized numerical features using StandardScaler.

### 8. Model Building

The following regression models were trained:

1. Linear Regression
2. Decision Tree Regressor
3. K-Nearest Neighbors (KNN) Regressor

### 9. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The model with the highest R² Score was selected as the best-performing model.

---

## 📊 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/mrunal332007/football-team-price-prediction.git
```

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook or Google Colab notebook.

4. Run all cells sequentially.

---

## 📈 Results

The project compares multiple regression algorithms and selects the model with the best prediction accuracy based on the R² Score.

---

## 📁 Project Structure

```text
├── Football_teams_price_data.csv
├── Football_Team_Price_Prediction.ipynb
├── README.md
```

---

## 👨‍💻 Author

Mrunal Patil

Machine Learning Project – Football Team Price Prediction
