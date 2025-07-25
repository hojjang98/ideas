# 🧠 Project Title: **Sweat Forecast: Predicting Pit Stain Risk by Hour**

## 🔍 Summary  
This project aims to develop a model that predicts the likelihood of **visible underarm sweat stains ("pit stains")** based on weather conditions, clothing color, activity level, and time of day. The goal is to help people make smarter clothing choices—especially in hot, humid summers—by telling them if it’s safe to wear gray today.

---

## 🎯 Problem Statement  
- Gray shirts are a risky fashion choice in summer.  
- Presentations, dates, interviews… pit stains can be embarrassing.  
- Yet, people rely on guesswork to pick what to wear.  
→ We need a **data-driven “pit stain alert” system**.

---

## 📚 Background & Motivation  
- Rising global temperatures and heat wave frequency  
- Clothes and colors show sweat differently (e.g., gray ≫ black or white)  
- Common online questions: “Can I wear a gray shirt today?”  
- Inspired by Reddit/Korean forums full of sweat-related wardrobe regrets

---

## 📊 Potential Data Sources  
- Hourly weather data (temperature, humidity) from national meteorological APIs  
- Sweat absorption/visibility by fabric & color (academic papers, product specs)  
- Wearable data (e.g., Fitbit, Apple Health: heart rate, step count)  
- Crowdsourced or scraped user comments: "I sweated like crazy today"  

---

## 🧪 Possible Approaches  
- Combine weather + activity + clothing info to build a **classification model**  
  (Logistic Regression, Random Forest, LSTM, etc.)  
- Assign "sweat visibility weights" by clothing material & color  
- Visualize risk with hourly heatmaps (e.g., 2 PM = maximum danger)  
- Build a simple mobile/web interface to display daily pit stain risk  
- Optional: Add shirt color recommendation system

---

## 💡 Expected Insights or Applications  
- A “Yes or No” system for wearing gray  
- A pit-stain forecast app with hourly risk scores  
- Context-aware clothing suggestion tool  
- Data-driven fashion decisions during heat waves  
- Potential for ad collaboration (e.g., deodorant brands, athletic wear)

---

## 🤡 Bonus Features  
- **“Pit Index” score** (0–100): Seoul at 89 = avoid gray at all costs  
- “Safe to raise arms” time window estimator  
- Could even host a fun mini Kaggle challenge: *Sweat Classification 2025*

