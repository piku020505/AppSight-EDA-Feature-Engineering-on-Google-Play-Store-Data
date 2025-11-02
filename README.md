# AppSight-EDA-Feature-Engineering-on-Google-Play-Store-Data

## 🧩 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** on the **Google Play Store dataset**.
The goal is to extract meaningful insights about app performance, user ratings, and market trends, while also preparing the dataset for potential machine learning applications.

The analysis highlights:

* Trends across app categories
* Relationships between app ratings, reviews, and installs
* Impact of price and content rating on popularity
* Data cleaning and feature engineering to handle inconsistencies

---

## 📊 Dataset

**Source:** Google Play Store public dataset (commonly used in Kaggle challenges)

**Key Columns:**

* `App` — Name of the application
* `Category` — Type of app (e.g., GAME, EDUCATION, TOOLS)
* `Rating` — Average user rating
* `Reviews` — Number of user reviews
* `Installs` — Total installs/downloads
* `Size`, `Price`, `Content Rating`, etc.

---

## 🧠 Project Workflow

1. **Data Loading & Inspection**

   * Import CSV file, check shape, info, and missing values
   * Identify categorical and numerical variables

2. **Data Cleaning**

   * Handle null/missing values
   * Remove duplicates
   * Convert columns like `Installs`, `Price`, and `Size` to numerical format

3. **Exploratory Data Analysis (EDA)**

   * Visualize distributions of ratings and installs
   * Category-wise analysis (Top 10 popular categories)
   * Correlation heatmaps for numerical features
   * Boxplots and pairplots for understanding relationships

4. **Feature Engineering**

   * Transform skewed variables
   * Encode categorical features (Label/One-hot Encoding)
   * Create new meaningful features such as `Price_Tier`, `Install_Bucket`, etc.

5. **Insights & Conclusions**

   * Identify categories that dominate the Play Store
   * Find factors that contribute to higher ratings
   * Understand user engagement metrics

---

## 🧰 Tech Stack

* **Programming Language:** Python
* **Libraries Used:**
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `sklearn`

---

## 🧾 Key Insights

* **Most popular categories:** Tools, Games, and Entertainment
* **Paid vs Free apps:** Free apps dominate in installs, but paid apps tend to have slightly higher ratings
* **App Size vs Rating:** Larger apps don’t always lead to better ratings
* **Feature Engineering Impact:** Created normalized and categorical features to make data ML-ready

---

## 📁 Project Structure

```
├── 3.0-EDA+And+FE+Google+Playstore.ipynb
├── data/
│   └── googleplaystore.csv
├── images/
│   └── visualizations.png
├── README.md
```

---

## 🚀 Future Work

* Apply machine learning models to predict **app success or rating**
* Automate feature selection pipeline
* Build an interactive dashboard using **Plotly Dash** or **Streamlit**

---
