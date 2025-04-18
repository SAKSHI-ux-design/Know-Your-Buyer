# Know-Your-Buyer
"Buy, Rent, Invest or Sell? A Data-Driven Approach to Real Estate Decision Making"

# 🧱 Brick by Brick – Predicting Real Estate Intent with Machine Learning

> A field project aimed at understanding and predicting consumer decision-making in the real estate sector using data analytics and machine learning.

---

## 📌 Project Objective

The objective of this project is to analyze consumer behavior in the Indian real estate market and develop a predictive model that can classify user intent into four categories: **Buying**, **Renting**, **Investing**, or **Selling** based on survey responses.

---

## 🗂️ Dataset Overview

### 🔍 Source

The dataset used in this project was **personally created by me** using **Google Forms** as part of a field project survey. It contains **102 individual responses** from various stakeholders in the real estate ecosystem — including buyers, sellers, investors, and agents.

### 📋 Structure

The form contained **18 multiple-choice questions** covering:
- Demographics
- Budget
- Property preferences
- Challenges
- Trust in technology
- Decision-making behavior

### 🔄 Data Processing

To prepare the dataset for machine learning:

- All **categorical responses** (like “Yes/No”, or “Apartment/Villa”) were **converted to numeric codes**.
- **Multi-option questions** (like amenities or decision factors) were transformed into **binary features (0 or 1)**.
- Missing or inconsistent values were cleaned.
- The final dataset included **independent variables (features)** and **one target variable** (`Interest`).

📁 Final dataset saved as: `responses.csv`

---

## 🧠 Key Questions Answered

- What type of property are people interested in?
- How do demographics and preferences influence their decision?
- Can we predict whether someone is going to buy, rent, invest, or sell?

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

---

## 🧪 Methodology

1. **Survey Design & Collection** – via Google Forms
2. **Data Cleaning** – removing inconsistencies and encoding values
3. **Feature Engineering** – converting responses into machine-readable format
4. **Model Training** – using Random Forest Classifier
5. **Evaluation & Prediction** – accuracy, feature importance, and sample predictions

---

## 📈 Sample Prediction

```python
# New user profile
Age = 30
Occupation = Buyer
Budget = ₹50-75 Lakhs
Property Type = Apartment
Important Factors = Location, Builder Reputation
Amenities = Parking, CCTV, Transit

# 🔍 Predicted Intent: **Buying**

