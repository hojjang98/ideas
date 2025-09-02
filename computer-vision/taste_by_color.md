# 🧠 Project Title: Taste by Color — Predicting Seasoning Levels from Food Images

## 🔍 Summary
Can the seasoning level of a dish (under-seasoned, well-seasoned, over-seasoned) be inferred **just by looking at it**?  
This project investigates whether **color and texture cues** in food images can predict seasoning intensity, inspired by the intuition of experienced army cooks.

---

## 🎯 Problem Statement
- Cooking apps and recipes rarely specify *how food should look* when properly seasoned.  
- Beginners struggle to identify under- or over-seasoning by appearance.  
- Experts often rely on color and sheen as strong indicators.  

**Goal:** Build a model that can visually judge seasoning levels, mimicking human intuition.

---

## 📚 Background & Motivation
- Originated from personal experience as a military cook:  
  *“I could tell whether food was salty or bland just by its color.”*  
- Color darkness, redness, or oiliness often correlate with flavor strength.  
- Potential uses in beginner cooking support, automated kitchens, or food photo review systems.

---

## 📊 Potential Data Sources
- YouTube cooking videos with subtitles mentioning taste (“too salty”, “a bit bland”)  
- Recipe blogs with dish photos and taste comments  
- Self-generated dataset: cooking the same recipe with varying seasoning levels  
- Public datasets or academic food image classification studies

---

## 🧪 Possible Approaches
- Image feature extraction: color histograms, brightness, saturation  
- Train CNN classifier: **under-seasoned / well-seasoned / over-seasoned**  
- Control for lighting differences or exclude artificially colored images  
- Data augmentation with GANs to simulate seasoning variations

---

## 💡 Applications
- **Cooking Assistant:** Suggest adjustments (“Your stew looks pale—add soy sauce”).  
- **Visual Tutorials:** Show learners what “properly seasoned” looks like.  
- **Food Industry:** Quality control in delivery or automated kitchens.  
- **Consumer Apps:** Fun mobile app scoring your dish’s taste by looks.

---

## ⚠️ Notes
- Must carefully handle lighting and camera bias.  
- Dataset creation is challenging without subjective human taste annotations.  
- Not about promoting food aesthetics alone, but practical cooking guidance.

---

## 🔗 Related Inspirations
- Chef intuition in large-scale kitchens (e.g., army cooks)  
- Food recognition/classification literature  
- Human-in-the-loop cooking assistance systems
