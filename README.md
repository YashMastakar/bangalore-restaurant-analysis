# 🍽️ Bangalore Restaurant Success Analysis (End-to-End Python Project)

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

---

## 📌 Project Overview

The **Bangalore Restaurant Success Analysis** is an **end-to-end exploratory data analysis project** aimed at identifying the key factors that contribute to restaurant success in Bangalore’s highly competitive food market.

This project analyzes **51,000+ restaurants** to uncover insights related to:
- Location
- Pricing strategy
- Online ordering
- Table booking
- Customer ratings & engagement

The goal is to help **new restaurant investors and business consultants** make **data-driven decisions**.

---

## 🎯 Business Problem

Bangalore has one of the most competitive restaurant ecosystems in India.  
A new restaurant group wants to enter the market but lacks clarity on:

- 📍 **Where to open**
- 🍽️ **What service model to adopt**
- 💰 **How to price their offerings**

This project identifies the **“Success Recipe”** using real-world restaurant data.

---

## 🧠 Business Persona

**Market Entry Consultant**

Helping restaurant investors:
- Reduce market-entry risk
- Choose optimal locations
- Optimize pricing & service strategy

---

## 📊 Dataset Information

- **Source:** Zomato Bangalore Restaurants Dataset (Kaggle)
- **Records:** 51,717 restaurants
- **Features:** Location, ratings, votes, cost, cuisines, online order, table booking, restaurant type

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – Data cleaning & manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis & storytelling
- **Exploratory Data Analysis (EDA)**

---

## 🔍 Key Analysis Performed

### 1️⃣ Data Cleaning
- Removed irrelevant columns
- Handled missing and invalid ratings (`NEW`, `-`)
- Cleaned cost columns
- Grouped low-frequency locations into `others`

### 2️⃣ Univariate Analysis
- Restaurant count by location
- Online ordering vs non-online ordering
- Table booking availability
- Restaurant type distribution

### 3️⃣ Bivariate Analysis
- Impact of **online ordering** on ratings
- Relationship between **cost and ratings**
- Location-wise rating comparison

### 4️⃣ Correlation Analysis
- Votes vs Ratings
- Cost vs Ratings
- Cost vs Popularity

---

## 📈 Key Insights

- ✅ **Online ordering is a baseline expectation**, not a differentiator
- 📉 **Table booking is underutilized**, offering premium positioning opportunities
- 📍 **Koramangala & MG Road** show high ratings with strong engagement
- 💰 **Higher price ≠ higher satisfaction**
- ⭐ **Customer engagement (votes)** is a stronger predictor of success than pricing

---

## 🧩 Strategic Business Recommendations

### 📍 Location Strategy
- Avoid highly saturated zones like **BTM**
- Target high-value areas:
  - Koramangala (4th & 5th Block)
  - Indiranagar
  - Whitefield
- Explore **low-competition “Others” locations** for niche dining

### 🍽️ Service Model
- Hybrid **Delivery + Dine-in**
- Introduce **table booking** to target premium customers

### 💰 Pricing Strategy
- Focus on **mid-range pricing**
- Balance quality perception with mass affordability

### 📢 Customer Engagement
- Encourage reviews & feedback
- High vote count correlates strongly with higher ratings

---

## 📂 Project Resources
For a detailed review of the full report, have a look at the files below:

* **[blr-resto-analysis-using-python.ipynb](./blr_resto_analysis.ipynb):** The complete Python code, including data cleaning, visualization, and statistical analysis.
* **[Bangalore_Resto_Success_Analysis.pdf](./BLR_Resto_Success_Analysis_Project.pdf):** The comprehensive project report exported from JupyterLab for a readable overview of all findings.
  
📊 Real World Dataset used:
https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

📘 Python Libraries Documentation:
https://pandas.pydata.org/docs/
https://seaborn.pydata.org/
https://matplotlib.org/stable/

📄 **License:** This project is licensed under CC BY-NC-ND 4.0.  
Commercial use or redistribution without permission is prohibited.

## 👤 Author
### Yash Mastakar
#### Aspiring Data Analyst | Python | SQL | Power BI | Data-Driven Decision Making

#### 📫 Open to Data Analyst & Business Analytics opportunities

#### ⭐ If you find this project useful, feel free to star the repository!
