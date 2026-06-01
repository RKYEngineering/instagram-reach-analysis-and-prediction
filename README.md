# 📊 Instagram Reach Analysis and Impression Prediction

![Project Banner](instagram_banner.png)

## 📌 Project Overview

Understanding what drives Instagram reach is important for creators, marketers, and businesses looking to grow their audience.

This project analyzes Instagram engagement data and builds a Machine Learning model to predict post impressions based on audience activity, content characteristics, and traffic sources.

The project includes:

* 🧹 Data Cleaning & Preprocessing
* 📊 Exploratory Data Analysis (EDA)
* ⚙️ Feature Engineering
* 🤖 Machine Learning Model
* 📈 Model Evaluation
* 💡 Business Insights

---

# 🎯 Project Objectives

* Analyze factors influencing Instagram reach
* Identify the strongest drivers of post impressions
* Build a machine learning model to predict impressions
* Evaluate model performance using regression metrics
* Generate actionable business insights

---

# 🗂️ Dataset Information

* **Dataset:** Instagram Reach Dataset
* **Records:** 5,000 Instagram posts
* **Target Variable:** Impressions
* **Features:** Post type, posting hour, engagement metrics, audience activity, traffic sources, captions, and hashtags

📌 **Note:** The dataset is synthetically generated and designed to simulate realistic Instagram engagement and reach patterns for learning and experimentation purposes.

---

# 🛠️ Technologies Used

| Category             | Tools               |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Analysis        | Pandas, NumPy       |
| Data Visualization   | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn        |
| Environment          | Google Colab        |

---

# 🔄 Project Workflow

## 📥 1. Data Collection

* Loaded Instagram reach dataset

## 🧹 2. Data Cleaning

* Removed duplicate records
* Checked missing values
* Converted date columns
* Extracted time-based features

## ⚙️ 3. Feature Engineering

Created:

* Caption Length
* Hashtag Count
* Engagement Rate

## 📊 4. Exploratory Data Analysis (EDA)

* Post Type vs Impressions
* Posting Hour Analysis
* Correlation Heatmap
* Likes vs Impressions Analysis
* Reach Source Analysis

## 🤖 5. Machine Learning Model

* Random Forest Regressor

## 📈 6. Model Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## 🔍 7. Feature Importance Analysis

* Identified the strongest factors influencing impressions

---

# 📌 Key Insights

* 🎥 Reels generated the highest average impressions
* ❤️ Likes were the strongest predictor of Instagram reach
* 👥 Profile Visits and Followers significantly influenced impressions
* 🔍 Home Feed, Explore, and Hashtag traffic contributed heavily to visibility
* 📝 Caption Length and Hashtag Count showed relatively low influence compared to engagement metrics

---

# 🚀 Model Performance

| Metric   | Score      |
| -------- | ---------- |
| R² Score | **0.96**   |
| MAE      | **15,380** |
| RMSE     | **22,343** |

---

# 📊 Results

* Successfully predicted Instagram post impressions
* Achieved an R² Score of **0.96**
* Identified the key drivers of Instagram reach
* Generated actionable insights for content optimization

---

# 💡 Business Impact

This project can help creators and businesses:

* 🎯 Improve content strategy
* 📈 Increase post visibility
* 📊 Understand audience behavior
* 🚀 Make data-driven publishing decisions

---

# 📂 Repository Structure

```text
instagram-reach-analysis/
│
├── data/
│   └── instagram_reach_dataset.csv
├── Instagram_Reach_Analysis_and_Prediction.ipynb
├── README.md
└── instagram-reach-analysis-banner.png
```

---

# 🔮 Future Improvements

* 🌐 Streamlit Deployment
* 🤖 XGBoost Model Comparison
* 📱 Social Media Dashboard
* 📊 Real-world Dataset Validation

---

## 👨‍💻 Author

**Ritik Kumar Yadav**

M.Tech Student | Aspiring Data Analyst

* LinkedIn: https://www.linkedin.com/in/ritik-kumar-yadav-70a81435a/
* GitHub: https://github.com/RKYEngineering

---

## ⭐ If you found this project useful, consider giving it a star!
