# 🧠 Project Title: **ColdPhish — Weather-Aware Human Vulnerability Analysis System**

## 🔍 Summary  
ColdPhish is an **AI-powered cybersecurity behavior analytics platform** that investigates how **environmental factors like temperature and season** influence human susceptibility to phishing attacks.  
By integrating weather data, email logs, and user response metrics, the system reveals **how external conditions affect internal security awareness** — uncovering the “human temperature” of cyber defense.  

---

## 🎯 Problem Statement  
- Most cybersecurity models focus solely on technical vulnerabilities, ignoring **human and environmental variables**.  
- Studies suggest that fatigue, stress, and cold weather can lower attention spans, potentially increasing **phishing click rates**.  
- Organizations lack tools to quantify how **weather conditions correlate with risky behaviors** in digital environments.  

**Goal:** Build a model that connects **real-world environmental data** (e.g., temperature, humidity, daylight hours) with **cyber behavior metrics** to forecast when users are most vulnerable to social engineering attacks.  

---

## 📚 Background & Motivation  
- Research in human factors and cognitive psychology indicates that **temperature changes can affect alertness and decision-making**.  
- Security teams often treat awareness training as static, even though **behavior fluctuates dynamically** with context.  
- By merging meteorological data and phishing analytics, we can design **adaptive defense strategies** that anticipate vulnerability spikes before they occur.  

---

## ⚙️ Key Features  
1. **Weather-Cyber Correlation Engine** – Collects regional weather data and merges it with phishing campaign logs.  
2. **Behavioral Vulnerability Scoring** – Computes a “Human Risk Index” based on click patterns vs. environmental conditions.  
3. **Adaptive Training Scheduler** – Automatically increases awareness campaigns during high-risk conditions (e.g., cold, dark, late afternoons).  
4. **Anomaly Visualization Dashboard** – Displays season-based heatmaps of phishing success rates and cognitive performance indicators.  
5. **LLM-based Context Analyzer** – Uses large language models to classify phishing emails by emotional tone (urgency, fear, trust cues).  

---

## 🧩 Technical Overview  
| Function | Technology | Description |
|-----------|-------------|-------------|
| Weather Data Integration | OpenWeatherMap / KMA API | Retrieves temperature, humidity, and daylight data by region |
| Phishing Log Parser | Pandas / Regex / SIEM Connector | Analyzes email response and click logs |
| Behavior Modeling | Scikit-learn / PyTorch | Predicts vulnerability probability using regression or anomaly detection |
| LLM Context Analysis | GPT-5 / Hugging Face Transformers | Classifies phishing email language features |
| Visualization & Reporting | Streamlit / Plotly | Interactive dashboards for risk and trend analysis |

---

## 🌱 Value Proposition  
- Introduces **season-aware security analytics** — connecting human behavior and environmental data.  
- Enables **predictive awareness training** instead of reactive education.  
- Strengthens **organizational cyber resilience** by forecasting “when” users are most likely to fail.  
- Opens a new dimension of **human-centric cybersecurity intelligence**.  

---

## 🚀 Potential Impact  
- Shifts cybersecurity culture from reactive alerts to **proactive behavioral insight**.  
- Provides CISO teams with data-driven timing for awareness campaigns.  
- Supports research into **environmental psychology + cybersecurity** — a novel interdisciplinary field.  
- Lays groundwork for “Adaptive SOC” models that integrate **contextual human factors** into security policy decisions.  
