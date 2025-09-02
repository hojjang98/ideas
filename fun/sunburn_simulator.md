# 🧠 Project Title: Sunburn Simulator — Predicting Your Post-Sun Tan with AI

## 🔍 Summary
Sunburn Simulator is an interactive tool that predicts how a user’s skin might tan or burn under current UV conditions.  
By combining **UV index, skin type, clothing, and sunscreen usage**, the system generates a **visual preview** of skin tone changes after sun exposure.

---

## 🎯 Problem Statement
- Many people underestimate the impact of **UV radiation** on skin.  
- Existing weather forecasts show UV index but don’t translate it into **personalized, intuitive effects**.  
- Users lack engaging tools to visualize the **direct impact** of their choices (time outdoors, sunscreen use, clothing).  

**Goal:** Build a simple, engaging simulator that promotes sun safety while offering fun, personalized insights.

---

## 📚 Background & Motivation
- Inspired by observing noticeable tanning among locals during a trip to Fukuoka, Japan.  
- Raised the question: *“What if we could simulate your skin tone after 30 minutes in today’s sun?”*  
- Combines playful interaction with **public health awareness**, encouraging better UV protection habits.  

---

## 📊 Potential Data Sources
- **UV Index**: NASA, NOAA, or local meteorological agencies.  
- **Skin Tone Data**: Fitzpatrick skin type classification datasets.  
- **Weather & Location APIs**: Real-time geolocation and forecasts.  
- (Optional) Image datasets for clothing coverage estimation.  

---

## 🧪 Technical Approach
1. **User Input**  
   - Location, exposure time, skin type, clothing coverage, sunscreen factor.  

2. **UV Dosage Calculation**  
   - Convert UV index and exposure duration into estimated skin damage risk.  

3. **Simulation Engine**  
   - Rule-based or ML models to map UV dosage → skin tone shift (HSV/RGB).  
   - (Optional) Apply simulated tone shifts to uploaded user photo.  

4. **Interface Development**  
   - Build demo app in **Streamlit** or **Gradio**.  
   - Provide “before vs after” visualization and prevention tips.  

---

## 💡 Applications
- **Public Health:** Encourage sunscreen use and safe sun behavior.  
- **Education:** Teach users how UV exposure varies by location and time.  
- **Consumer App:** Fun mobile app for daily use, with shareable results.  
- **Portfolio Project:** Combines CV, health tech, and UX design for strong demonstration.  

---

## ⚠️ Notes
- Skin response to UV varies by genetics and environment → predictions are approximations.  
- Needs careful messaging to avoid medical overpromises.  
- Clothing and sunscreen data may be difficult to standardize.  

---

## 🔗 Related Inspirations
- UV forecast apps with health warnings.  
- Fitzpatrick skin type classification research.  
- Interactive health-visualization projects.  

---

> “See tomorrow’s tan today — and protect your skin before it’s too late.”
