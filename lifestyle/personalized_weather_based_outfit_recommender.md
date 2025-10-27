# 🧠 Project Title: Wearly — Personalized Weather-Based Outfit Recommender  

## 🔍 Summary  
**Wearly** is a smart fashion assistant that recommends **what to wear based on how you’ll actually feel**, not just the temperature.  
By combining weather data (temperature, humidity, wind, sunlight) with personal comfort preferences, it delivers **context-aware outfit and accessory suggestions** such as:  
> “It’s breezy today — a light jacket and a scarf would be perfect 🧣.”  

This AI-driven service helps users dress comfortably and stylishly while minimizing daily guesswork.  

---

## 🎯 Problem Statement  
- Most people decide what to wear based **only on temperature**, ignoring factors like wind chill or humidity.  
- **Perceived comfort** varies by individual (some feel cold more easily).  
- Mornings and evenings can differ drastically in temperature, leading to discomfort throughout the day.  

**Goal:** Build an intelligent system that predicts **“how cold or warm you’ll feel”** and recommends the **right outfit layers and accessories** accordingly.  

---

## 📚 Background & Motivation  
- Current weather apps provide numerical forecasts but lack **personalized, actionable insights** (“what should I wear?”).  
- People often regret their clothing choices because they misjudge *wind*, *sun exposure*, or *humidity*.  
- With increasing interest in **personal comfort analytics**, Wearly bridges fashion, weather data, and behavioral AI.  

---

## 💡 Possible Features  
1. **Feel-Temperature Prediction**  
   - Calculates *personalized perceived temperature* using wind, humidity, sunlight, and individual sensitivity.  
2. **Layer & Accessory Recommendations**  
   - Suggests outfits (e.g., “hoodie + windbreaker”) and items like scarves, gloves, or sunglasses.  
3. **Daily Scenario Forecast**  
   - Morning vs. evening clothing adjustments: “You’ll feel fine at noon but cold after sunset — bring a scarf.”  
4. **Feedback Loop AI**  
   - Users rate comfort (“too cold / just right / too hot”) → model learns individual preferences over time.  
5. **Visual / Avatar Mode**  
   - 3D AI character demonstrates suggested outfits or tones: “Today’s vibe? Soft brown layers ☁️.”  

---

## 📊 Potential Data Sources  
- Public weather APIs (OpenWeatherMap, 기상청 API).  
- Historical comfort indexes (wind chill, heat index).  
- User profile data (gender, body type, temperature sensitivity).  
- Daily feedback and time-of-day logs.  

---

## 🧪 Technical Approach  
1. **Data Integration** – Collect weather and user-specific parameters.  
2. **Feature Engineering** – Compute perceived temperature, sun exposure, humidity comfort index, etc.  
3. **Recommendation Model** – Use ML (e.g., LightGBM, XGBoost) to map conditions → outfit category.  
4. **Personalization Layer** – Apply learned bias per user (“cold-sensitive,” “commutes by bike,” etc.).  
5. **Front-End Interface** – Streamlit or mobile app with visual outfit recommendations and notifications.  

---

## 💡 Applications  
- **Daily Use:** Fast, data-driven outfit suggestions for individuals.  
- **Workplaces:** Group notifications (e.g., “office scarf day” when cold).  
- **Smart Home Integration:** Link with smart mirrors or wardrobes.  
- **Fashion Retail:** Dynamic product suggestions based on weather.  

---

## ⚠️ Notes  
- Avoid generic advice; ensure **tone and warmth of recommendation feel natural and human-like.**  
- Emphasize **personal learning** — model improves accuracy through user feedback.  
- Keep privacy strong; no unnecessary personal tracking.  

---

## 🔗 Related Inspirations  
- Smart mirrors and virtual closet apps.  
- Personalized fitness/weather comfort trackers.  
- Behavioral models of thermal comfort and clothing decisions.  

---

> “Stop guessing what to wear — let the weather and AI dress you just right.”
