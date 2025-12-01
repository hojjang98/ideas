# 🧠 Project Title: Circadian Wellness Manager (Chrono-Sense)
> AI-Driven Environmental Optimization for Personalized Fatigue and Sleep Cycle Management.

---

## 🔍 Summary
Chrono-Sense is an AI-driven Personal Environment Optimization (PEO) system that analyzes a user's current fatigue type (physical, cognitive, seasonal) and proactively adjusts their immediate environment (light color temperature, intensity, acoustic frequency, temperature) in real-time. The system specifically targets **hormonal imbalances caused by reduced sunlight exposure** (a key factor in winter fatigue) by utilizing personalized light and sound protocols to actively combat fatigue and improve sleep quality.

---

## 🎯 Problem Statement
- **Non-Personalized Solutions:** Existing smart lighting and wellness apps offer static, generic patterns and fail to account for a user's **real-time hormonal state or cognitive load.**
- **Passive Management:** Fatigue management is typically **reactive** (resting *after* feeling exhausted), making proactive energy and well-being management difficult.
- **Seasonal Impact:** Fatigue and lethargy are exacerbated in winter due to **reduced serotonin and increased melatonin** caused by low light exposure, a systemic problem lacking an integrated solution.

**Goal:** Replace the existing **passive, one-size-fits-all rest approach** with a smarter, user-centered, and **proactive environmental control system** that synchronizes with the user's biological clock.

---

## 💡 Motivation & Background
The motivation for Chrono-Sense stems from the scientific evidence linking **diminished sunlight exposure** (especially in winter) to chronic fatigue, sleep rhythm disruption, and reduced cognitive performance due to hormonal imbalance (Serotonin/Melatonin). I observed a crucial gap where current wearables measure *results* (sleep time, heart rate) but fail to actively *change* the environment to prevent the fatigue source. This project aims to create a dynamic, personalized "digital sun" and "wellness shield" that optimizes neurochemistry through environmental cues.

---

## 💡 Key Objectives
1. **Bio-Signal Integration:** Develop an API layer to ingest real-time physiological data (HRV, skin temperature, movement) from wearables to infer fatigue type.
2. **Adaptive Environmental Model:** Create an AI model that maps specific fatigue states to optimal light (lux, Kelvin) and sound (binaural beats, nature sounds) parameters.
3. **Proactive Intervention Engine:** Implement a rule-based engine that triggers subtle environmental changes *before* the user consciously recognizes a performance or energy dip.

---

## 🧩 Core Differentiators

| Aspect | Existing Systems (Smart Lights/Sleep Trackers) | **This Idea (Chrono-Sense)** |
|:---|:---|:---|
| Comparison 1 | Focuses on **fixed schedules** (e.g., wake-up light) | Focuses on **real-time biometrics** and immediate needs |
| Comparison 2 | Outputs **data visualization** (How you slept) | Outputs **environmental change** (How you should feel now) |
| Comparison 3 | Simple **color/brightness change** | **Multi-modal optimization** (Light + Sound + Temp, including binaural beats) |

---

## ⚙️ System Architecture
**Input:** Wearable Data (HRV, Sleep Stages, Movement), Ambient Sensor Data (Ambient Light, Temperature, Humidity), User Input (Self-Reported Mood/Fatigue Level).
**Process:**
1. **Fusion Layer:** Cleans and aggregates multi-source time-series data.
2. **Fatigue Classification Model:** Uses a time-series model (LSTM) to classify the user's state (e.g., 'Cognitive Overload', 'Melatonin Spike', 'Physical Recovery').
3. **Optimization Engine:** Calculates the necessary environmental change (e.g., Increase 6500K light by 500 lux, play 10Hz Alpha Waves).
**Output:** Control Signal to Smart Home Hub (Dimmable Lights, Smart Speaker, HVAC).

---

## 📦 Technology Stack
- **Backend:** Python (FastAPI) for API handling and real-time computation.
- **Model / AI:** LSTM or Time-Series Forecasting Model (for predicting fatigue onset).
- **Frontend:** Mobile Application (Flutter or React Native) for user mood logging and visualization.
- **Database:** PostgreSQL (for time-series data storage and analysis).
- **Libraries:** Pandas/NumPy, TensorFlow/PyTorch, OpenHAB/Home Assistant Integration Libraries.

---

## 🚀 Use Cases
- **Winter Fatigue Combat:** Simulates a **"Digital Sunrise"** by gradually emitting high-intensity (6500K) light 30 minutes before wake-up to suppress melatonin and facilitate alertness.
- **Cognitive Recovery:** Upon detecting a drop in cognitive performance (via HRV analysis), the system subtly shifts lighting to a **warmer tone (3000K)** and plays **Binaural Beats** to encourage a brief, restorative mental break.
- **Shift Work Adjustment:** Calculates the user's required new sleep rhythm and precisely regulates lighting and temperature to aid biological clock adaptation, regardless of the external environment.

---

## 🌐 Future Extensions
- **Nutrient Correlation:** Integrate with food tracking apps to suggest nutrient (e.g., Vitamin D, Tryptophan) intake based on predicted seasonal fatigue levels.
- **Haptic Feedback:** Integrate with smart furniture or clothing to provide gentle haptic stimulation to maintain alertness or induce calm.
- **Emotional AI:** Integrate facial recognition or voice analysis to instantly detect acute stress and trigger immediate calm protocols.

---

## 🧭 Vision
> “To seamlessly manage the human body's energy and mood by making the surrounding environment an invisible, intelligent extension of personal well-being.”