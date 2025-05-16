# Inside Airbnb 🏙️  
**The Impact of Location and Listing Features on Guest Experience in NYC**

## 📘 Overview  
This project investigates how geographic location and listing features influence guest satisfaction on Airbnb in New York City. Using data from Inside Airbnb, we apply clustering, regression modeling, and visualization techniques to identify key patterns in guest ratings. Our findings offer actionable insights for both Airbnb hosts and platform designers.

---

## 🎯 Objectives  
- Analyze the relationship between **location** and **guest review scores**.
- Identify which **listing features** (e.g., price, room type, superhost status) drive guest satisfaction.
- Provide data-driven recommendations to improve listing strategies and platform design.

---

## 🧪 Methodology  
### Research Question 1: Does location affect review scores?  
- **Techniques Used**:
  - K-means clustering on geographic coordinates
  - ANOVA & Kruskal-Wallis tests
  - PCA on latitude & longitude
- **Insight**: Listings in central NYC (e.g., Manhattan, Brooklyn) generally score higher.

### Research Question 2: What listing features drive satisfaction?  
- **Techniques Used**:
  - Multiple Linear Regression
  - Variance Inflation Factor (VIF) analysis
  - Visualization (box plots, scatter plots)
  - PCA on numeric features
- **Insight**: Being a Superhost, review count, and room type have strong influence.

---

## 📊 Key Findings  
- Superhost status is the strongest predictor of higher ratings.
- Private or hotel-style rooms tend to receive lower scores than entire homes.
- Spatial clusters aligned with boroughs show significant review score differences.
- Listings in central areas and those with more reviews perform better.

---

## 📂 Data Description  
- Source: [Inside Airbnb](http://insideairbnb.com/get-the-data)
- Listings: 37,785 in NYC  
- Variables: 58 cleaned features including property type, host stats, pricing, and reviews  
- Output: `listings_cleaned.csv`

---

## 🔧 Tools & Technologies  
- **Language**: R  
- **Libraries**: `dplyr`, `ggplot2`, `stats`, `factoextra`, `car`  
- **Techniques**: K-means, PCA, MANOVA, Linear Regression, VIF, Visual Analysis

---

## 📌 Limitations  
- Some missing data (~11,000 entries) impacted statistical power.
- Results are specific to NYC; may not generalize across cities.
- PCA and cluster interpretations depend on preprocessing quality.

---

## 🧠 Conclusion  
This analysis confirms that both **where a listing is** and **what it offers** significantly influence guest satisfaction. Hosts and platform designers can optimize by focusing on service quality, transparent descriptions, and leveraging geographic advantages.

---

## 👥 Contributors  
- Victor Zhan  
- Yilin Xiao  
- Violet Yong  
- Yuqi Wang
