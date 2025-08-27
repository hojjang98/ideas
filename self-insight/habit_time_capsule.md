# 🧠 Project Title: **Habit Time Capsule — Data-Driven Future Self Simulator**

## 🔍 Summary  
Habit Time Capsule lets users **log daily habits** and runs **data-driven simulations** to show how those habits could compound over **1/3/6/12 months**.  
Unlike chat-based “future self” apps, it focuses on **quantitative forecasts, counterfactuals, and shareable infographics** that make long-term change tangible.

---

## 🎯 Key Features  

### 1. Habit Logging & Analytics  
- Quick inputs via **toggle, slider, text, or voice** (e.g., study hours, workout intensity, savings amount, sleep duration).  
- Automatic **domain tagging** (Fitness, Study, Finance, Sleep) and **quality scoring** (intensity, consistency).  
- **Adherence model** estimates the likelihood of keeping each habit; **“Trajectory Meter”** visualizes daily momentum.

### 2. Multi-Domain Forecast Engine  
- Domain-specific models map habits → outcomes:  
  - **Fitness**: weight/body-fat trend, 1RM estimate, VO₂max proxy.  
  - **Study**: cumulative hours, spaced-repetition retention proxy, vocab/problem counts.  
  - **Finance**: savings/investment growth with adjustable rate/risk.  
  - **Sleep**: efficiency score, daytime fatigue proxy.  
- Forecasts include **confidence bands** and **milestone projections** (e.g., “reach 10M won by March”).

### 3. Counterfactual & What-If Studio  
- Compare scenarios side-by-side: **maintain vs. +10% effort vs. −20% drop**.  
- Show **drivers of change** (feature importance) and **small-lever nudges** (e.g., +10 min/day study → +X outcomes).  
- Weekly **“tipping-point” alerts** when tiny habit tweaks could flip the curve.

### 4. Time-Capsule Playback (Media + Forecast Overlay)  
- Record a short **“Dear Future Me”** note (text/voice/video) and set an unlock date.  
- On unlock, auto-play the message with an **overlay comparing predicted vs. actual** progress.  
- Generates a personal **highlight reel** of key streaks and milestones.

### 5. Personalized Infographic Reports  
- Monthly **auto-generated infographic/PDF** summarizing trends, forecasts, and best levers.  
- Clean visuals for **progress share** (optional), with privacy-safe stats and badges.

---

## 📊 Technology Stack  
- **Modeling/Forecasting**: PyTorch (domain models), scikit-learn/LightGBM (adherence & feature importance), PyMC/Prophet (uncertainty & seasonality).  
- **NLP/Voice**: Whisper (STT) for voice logging, optional TTS for future-self messages.  
- **Frontend**: Flutter (mobile), React (web).  
- **Backend**: FastAPI + PostgreSQL (TimescaleDB for time-series).  
- **Visualization**: Plotly, D3.js for forecasts and infographics.  

---

## 💡 Unique Selling Points  
- Shifts focus from **qualitative future-self chats** to **quantitative simulations**.  
- Provides **counterfactual comparisons** and **nudges** to strengthen motivation.  
- Merges **time-capsule journaling** with **data-backed projections**.  
- Delivers **sharable monthly infographics** for motivation and accountability.  
