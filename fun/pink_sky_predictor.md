# 🧠 Project Title: Pink Sky Predictor — Forecasting Magical Evenings

## 🔍 Summary
Pink Sky Predictor is a system that forecasts the likelihood of **pink-colored sunsets** using weather and atmospheric data.  
It aims to help photographers, travelers, and outdoor lovers plan activities and capture beautiful moments with **data-driven “pink sky alerts.”**

---

## 🎯 Problem Statement
- Pink skies are visually stunning but highly unpredictable.  
- Current weather forecasts provide sunset times but not **sky color conditions**.  
- People often miss the chance or get disappointed by dull skies.  

**Goal:** Build a predictive model that estimates the probability of pink skies at sunset.

---

## 📚 Background & Motivation
- Pink skies result from **light scattering** (Rayleigh/Mie) and atmospheric particle interactions.  
- Standard meteorology overlooks **aesthetic sky outcomes**.  
- Social media trends (#pinksky, #오늘하늘) spike on days with colorful sunsets, offering a proxy signal for labeling.  

---

## 📊 Potential Data Sources
- Meteorological data: humidity, temperature, cloud cover, precipitation.  
- Air quality data: PM2.5, dust, pollution indices.  
- Satellite imagery (NASA MODIS, Himawari).  
- Crowdsourced data: social media image posts with sunset hashtags.  

---

## 🧪 Technical Approach
1. **Data Preparation**  
   - Collect meteorological + air quality features.  
   - Label training data using social media images and hashtags.  

2. **Modeling**  
   - Classification models: Logistic Regression, Random Forest, XGBoost.  
   - Multimodal model combining tabular features with image embeddings.  

3. **Deployment**  
   - Web/mobile app showing **Pink Sky Index**.  
   - Evening notifications for high-probability days.  

---

## 💡 Applications
- **Lifestyle:** Alerts for romantic walks, evening picnics, outdoor gatherings.  
- **Photography/Tourism:** Tools for photographers and city marketing campaigns.  
- **Science:** Insights into how pollution and weather shape aesthetic phenomena.  

---

## ⚠️ Notes
- Subjectivity in “pink sky” perception → requires robust labeling.  
- High variability due to local microclimates.  
- Satellite and social media data may introduce latency or noise.  

---

## 🔗 Related Inspirations
- Air quality and weather forecasting APIs.  
- Social-media-based environmental sensing projects.  
- Kaggle competitions combining meteorology and image recognition.  

---

> “Never miss a magical sunset again — let data predict beauty.”
