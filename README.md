# 🎬 Personalized Movie Recommendation System

## 📌 Problem Statement
The primary goal is to develop a **personalized movie recommendation system** that enhances user experience by suggesting movies based on user ratings and those of similar users. The system leverages **collaborative filtering techniques**, including:
- **Item-based & User-based approaches**
- **Matrix factorization methods**

---

## 🔍 Key Observations
- **Class Imbalance:** 82% of ratings are **3, 4, or 5 stars**, indicating a bias in user preferences.
- **Popular Genres:**
  - 🎭 **Comedy & Drama** are the most rated genres.
  - 👥 Users under **35** tend to rate comedy movies more frequently.
- **Demographic Trends:**
  - Significant correlation between **users' age and occupations**.
  - 🎯 Targeting **ages 25-34** with Comedy & Drama can be effective.
- **Seasonal Trends:**
  - Peak rating periods: **Week 47 (late November) - 17%** & **Week 31 (late July/August) - 8%** (holidays, summer breaks).
- **Genre Trends (2000-2003):**
  - 📉 **Declining:** Documentary, Animation, Children, Sci-Fi, Horror.
  - 📈 **Increasing:** Crime, Film Noir, Musical, Romance, War.
- **Genre Correlations:**
  - 🎞 **Animation & Children** genres are strongly correlated.
  - 🎬 **Action, Adventure, and Sci-Fi** share a strong link.

---

## 📊 Recommendations
✅ **Targeted Marketing**: Focus on the **25-34 age group**, emphasizing popular genres (Comedy & Drama).  
✅ **Leverage Seasonal Trends**: Optimize releases & promotions around **Week 47 & Week 31**.  
✅ **Content Strategy**:
   - Increase production in **rising genres** (Crime, Romance, Musical, Film Noir, War).  
   - Revitalize **declining genres** (Animation, Sci-Fi) with fresh content.  

---

## 🚀 Simplified Summary of Work
- Used **Pearson & Cosine similarity matrices** for recommendations.
- Evaluated models using **MAPE & RMSE**:
  - **CMF Model (𝑑=4) - Context-based Factorization:**
    - 📉 **MAPE**: **27.71%**
    - 📊 **RMSE**: **0.9037**
    - 🔍 **MSE**: **0.8166**
  - **XGBoost Model:**
    - 📉 **MAPE**: **34.99%**
    - 📊 **RMSE**: **1.0585**
    - 🔍 **MSE**: **1.1204**

---

🎯 **This recommendation system aims to refine user experience by delivering accurate, meaningful movie suggestions while leveraging demographic and seasonal insights for enhanced engagement.**

