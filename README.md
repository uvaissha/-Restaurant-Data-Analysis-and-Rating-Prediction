# 🍽️ Restaurant Data Analysis and Rating Prediction

**Internship Project @ Cognifyz Technologies**

This project involves end-to-end analysis and machine learning modeling on a restaurant dataset to uncover insights and predict aggregate ratings. A Streamlit-based web interface is also developed to make data interaction more intuitive and user-friendly.

---

## 🚀 Objective
To explore, clean, analyze, and model restaurant data to:
- Understand customer preferences and restaurant trends
- Predict restaurant ratings using machine learning
- Build an interactive web app using Streamlit

---

## 📂 Dataset Overview
The dataset contains information such as:
- Aggregate Ratings
- Cuisines
- Country and City
- Price Range
- Table Booking & Online Delivery
- Location Coordinates
- Customer Votes

---

## ✅ Project Phases

### 🔍 Level 1: Exploratory Data Analysis & Preprocessing
- **Data Cleaning:** Handled missing values, fixed data types
- **Descriptive Stats:** Explored key distributions (e.g., cuisines, cities)
- **Geospatial Analysis:** Mapped restaurant locations by city and country

### 📊 Level 2: Advanced Insights & Feature Engineering
- **Booking & Delivery Trends:** Found correlations with ratings
- **Price Range Analysis:** Identified highly rated price segments
- **Feature Engineering:** Created useful new features (e.g., cuisine count)

### 🤖 Level 3: Modeling & Visualization
- **ML Models:** Built and evaluated Linear Regression, Decision Tree, Random Forest
- **Performance:** Random Forest showed best accuracy
- **Visualizations:** Histograms, bar plots, scatter plots, heatmaps, maps

---

## 🌐 Web Interface
An interactive web interface was built using **Streamlit** to:
- Display data insights and visualizations
- Accept user input for restaurant features
- Predict restaurant rating in real-time using the trained model

Run locally:
```bash
streamlit run app.py
