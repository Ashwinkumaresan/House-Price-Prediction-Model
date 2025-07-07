# 📊 House Price Prediction

This project focuses on predicting house prices using a regression-based machine learning approach. It involves exploratory data analysis, correlation studies, and the development of a linear regression model to estimate house prices based on various features like the number of bedrooms, bathrooms, square footage, and more.

---

## 📁 Dataset

The dataset used contains information about **4600 houses** including:

- **price**
- **bedrooms**
- **bathrooms**
- **sqft_living**
- **sqft_lot**
- **floors**
- **waterfront**
- **view**
- **condition**
- **sqft_above**
- **sqft_basement**
- **year built**
- **year renovated**
- **street**
- **city**
- **statezip**
- **country**

**File:** `data.csv`

---

## 📌 Project Workflow

1. **Data Loading** - Load and inspect the dataset using Pandas.
2. **Exploratory Data Analysis** - Examine correlations between house price and other features.
3. **Data Cleaning** - Drop unnecessary columns like `date`, `street`, and `country`.
4. **Encoding** - Convert categorical values (`city`, `statezip`) into numerical codes.
5. **Model Development** - Build and train a **Linear Regression model**.
6. **Evaluation** - Measure the model’s performance using metrics like **R² score** and **RMSE (Root Mean Squared Error)**.
7. **Prediction** - Predict house prices based on new input data.

---

## 📦 Requirements

Install the required Python packages using:

pip install -r requirements.txt

## 📈 Results

The trained Linear Regression model produced the following evaluation metrics:

  * **R² Score:** `0.7163`
  * **MAE:** `106,734.54`
  * **MSE:** `31,904,500,843.77`
  * **RMSE:** `178,618.31`

-----

## 🖥️ Sample Output

When you run the final evaluation cell in the notebook, you’ll see output like this:


## 🖥️ Sample Output

When you run the final evaluation cell in the notebook, you’ll see output like this:

```
R² Score: 0.7163887680090901
MAE: 106734.54877224304
MSE: 31904500843.76988
Root Mean Squared Error: 178618.31049410885
```

-----

## 📌 Key Takeaways

  * 📊 **Linear Regression** effectively models house price predictions when numerical and categorical data are properly cleaned and encoded.
  * 🔍 **Correlation analysis** clearly identifies which features most influence house prices (like `sqft_living`, `bedrooms`, etc.).
  * 📉 Proper **data preprocessing** (dropping irrelevant columns, encoding categories) improves model accuracy.
  * 📈 Regression performance is best understood through combined metrics: **R² score**, **MAE**, **MSE**, and **RMSE**.
  * 📝 This workflow provides a solid baseline for extending to more complex models like **Random Forest** or **Gradient Boosting** in future iterations.

-----

## 🚀 How to Run

1.  Clone this repository.
2.  Place your `data.csv` file in the same directory.
3.  Open `HousePricePrediction.ipynb` using Jupyter Notebook.
4.  Run all the cells to execute the workflow and view predictions.

-----
