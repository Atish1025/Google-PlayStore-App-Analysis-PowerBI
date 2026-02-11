<img width="1820" height="772" alt="Screenshot 2026-02-11 124828" src="https://github.com/user-attachments/assets/14d5a1f3-8d45-4b4c-b8d6-ae1bc679b741" />
---

# 📊 Google Play Store App Analysis – Power BI Dashboard & EDA

## 📌 Project Overview

The Google Play Store hosts millions of Android applications across diverse categories, generating extensive user interaction data in the form of installs, ratings, reviews, pricing information, and feedback.

This project focuses on analyzing Google Play Store app data along with user review sentiment data to identify the key factors that drive app engagement, popularity, and overall success.

The project combines **Exploratory Data Analysis (EDA)** using Python and an interactive **Power BI Dashboard** to transform raw data into actionable business insights.

---

## 🎯 Business Objective

The primary objective of this project is to:

* Identify factors influencing app installs and engagement
* Analyze the relationship between ratings, reviews, and downloads
* Compare performance of Free vs Paid apps
* Evaluate category-wise app performance
* Understand user sentiment impact on app success

The dashboard enables stakeholders to make **data-driven decisions** for improving app performance and market reach.

---

## 📂 Datasets Used

### 1️⃣ Google Play Store App Dataset

Contains:

* Category
* Rating
* Reviews
* Installs
* App Size
* Price
* Type (Free / Paid)
* Content Rating
* Genres

### 2️⃣ User Review Dataset

Contains:

* App Name
* Translated Review
* Sentiment (Positive / Neutral / Negative)
* Sentiment Polarity
* Sentiment Subjectivity

---

## 🛠 Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* **Power BI**
* Jupyter Notebook
* GitHub

---

## 🧹 Data Cleaning & Preparation

* Removed missing and inconsistent values
* Converted installs and price columns into numerical format
* Standardized app size values
* Removed duplicate records
* Performed sentiment validation
* Ensured proper data types for analysis

---

## 🔍 Key Analysis Performed

### 📊 1. Rating Distribution Analysis

Most apps have ratings between 4.0 and 4.5, indicating generally positive user satisfaction.

### 📊 2. Category Performance Analysis

Categories such as Games and Communication show significantly higher installs, indicating strong user demand.

### 📊 3. Free vs Paid App Comparison

Free apps dominate installs due to lower entry barriers, while paid apps may focus more on niche markets.

### 📊 4. Rating vs Installs Relationship

Higher-rated apps generally receive more installs, though ratings alone do not guarantee success.

### 📊 5. Correlation Analysis

Reviews and installs show a strong positive correlation, highlighting user engagement impact.

### 📊 6. Sentiment Analysis

Most user reviews are positive, aligning with overall high ratings across apps.

---

## 📈 Power BI Dashboard Features

The interactive dashboard includes:

* KPI Cards (Total Apps, Total Installs, Average Rating, Total Reviews)
* Category-wise Install Analysis
* Free vs Paid Distribution
* Rating vs Installs Scatter Plot
* Sentiment Distribution Chart
* Interactive Filters for Category & App Type

---

## 📷 Dashboard Preview

![Uploading Screenshot 2026-02-11 124828.png…]()


```

```

---

## 💡 Key Insights

* Free apps achieve higher installs compared to paid apps.
* Ratings and reviews significantly influence app downloads.
* Certain categories dominate user engagement.
* Positive sentiment aligns with better app performance.
* User engagement metrics strongly correlate with app popularity.

---

## 🧠 Stakeholder Value

* **App Developers:** Improve app quality and optimize features
* **Product Managers:** Identify high-performing categories and pricing strategies
* **Marketing Teams:** Target high-engagement segments
* **Business Leaders:** Make data-driven investment decisions

---

## 📁 Repository Structure

```
Google-PlayStore-App-Analysis-PowerBI/
│
├── data/
├── notebook/
├── powerbi/
├── images/
└── README.md
```

---

## 🏁 Conclusion

This project demonstrates how exploratory data analysis and interactive data visualization can transform raw Google Play Store data into meaningful business intelligence. By combining numerical metrics with sentiment insights, the analysis provides a comprehensive understanding of app engagement and market performance.

The Power BI dashboard enables stakeholders to explore insights interactively and make informed decisions to enhance app success in a competitive marketplace.

---
