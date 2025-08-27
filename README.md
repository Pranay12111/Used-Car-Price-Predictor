# 🚗 Used Car Price Predictor

## 📌 Project Overview

The **Used Car Price Predictor** is a machine learning project designed to estimate the resale price of used cars based on key features such as brand, year of manufacture, mileage, fuel type, transmission, and other specifications.

The goal is to build a predictive model that helps buyers and sellers make **data-driven decisions** while minimizing guesswork in pricing.

---

## 📂 Dataset

* **Source:** Publicly available car resale datasets (Kaggle / scraped / custom collected)
* **Size:** \~X,XXX records (varies by dataset)
* **Features Include:**

  * `Car_Name` – Brand and model
  * `Year` – Year of manufacture
  * `Present_Price` – Current ex-showroom price (in Lakhs)
  * `Kms_Driven` – Kilometers driven
  * `Fuel_Type` – Petrol / Diesel / CNG
  * `Seller_Type` – Dealer / Individual
  * `Transmission` – Manual / Automatic
  * `Owner` – Number of previous owners
  * `Selling_Price` – (Target variable) Used car resale price

---

## 🛠️ Tools & Technologies

* **Python** 🐍
* **Libraries:**

  * `pandas` → Data cleaning & preprocessing
  * `numpy` → Numerical computations
  * `matplotlib` & `seaborn` → Data visualization
  * `scikit-learn` → Model building & evaluation
  * `pickle / joblib` → Model saving & deployment

---

## 🔍 Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical features (Fuel Type, Transmission, Seller Type)
   * Feature scaling & transformation

2. **Exploratory Data Analysis (EDA)**

   * Distribution of car prices
   * Relationship between price and car age, mileage, brand
   * Correlation heatmap of numerical features

3. **Model Building**

   * Tested regression models:

     * Linear Regression
     * Decision Tree Regressor
     * Random Forest Regressor
     * Gradient Boosting (XGBoost/LightGBM)
   * Selected best-performing model based on **R² Score & RMSE**

4. **Model Evaluation**

   * Train/Test Split
   * Cross-validation for robustness
   * Residual analysis

5. **Deployment (Optional)**

   * Exported trained model as `.pkl` file
   * Built a simple web app using **Flask/Streamlit** for price prediction

---

## 📊 Example Insights

* **Car Age:** Older cars depreciate faster in price.
* **Fuel Type:** Diesel cars retain slightly higher resale value than petrol in certain segments.
* **Transmission:** Automatic cars generally fetch higher resale prices.
* **Owner Count:** Cars with more than 1 previous owner show sharp price drops.

---

## 🚀 Project Outcomes

* A **trained ML model** that predicts used car prices with high accuracy.
* **Interactive interface (if deployed)** to input car details and get instant predictions.
* Valuable insights into factors affecting car resale pricing.

---



## 📌 Future Enhancements

* Incorporate **real-time car listing data** from marketplaces.
* Use **deep learning models** (ANNs) for improved accuracy.
* Deploy as a **full-stack web app** with React/Angular frontend.
* Integrate with **cloud services** (AWS/GCP/Azure) for scalability.

---

## 🙌 Acknowledgments

* **Dataset Providers** (Kaggle / Public APIs)
* **Scikit-learn & Streamlit Communities** for open-source resources

---
