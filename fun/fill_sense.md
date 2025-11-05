# 🧠 Project Title: **FillSense — Guess the Inside of Food**  

---

## 🔍 Summary  
**FillSense** is a fun AI experiment that predicts the *hidden filling* of foods like **붕어빵, 송편, 찐빵, 만두** based solely on their outer appearance.  
By training a vision model to infer internal ingredients from subtle visual cues (shape, color tone, puffiness, surface patterns), it explores whether AI can “imagine” what’s inside without cutting the food open.  

---

## 🎯 Problem Statement  
- Foods like 붕어빵 or 송편 have **identical outer shapes**, making it hard to know the filling until you bite.  
- Even humans often rely on **experience or guesswork**, not visual reasoning.  
- No playful system exists that combines **computer vision** and **culinary curiosity** in this way.  

**Goal:** Build a lightweight, AI-powered guessing system that predicts a food’s filling from its appearance.  

---

## 💡 Key Objectives  
1. Collect a small dataset of filled foods (붕어빵, 송편, 만두, 찐빵) with labeled fillings.  
2. Train a CNN-based classifier to infer the likely filling type (e.g., red bean, cream, sweet potato, chocolate).  
3. Visualize prediction confidence and “food intuition” through a simple, fun interface.  

---

## 🧩 Core Differentiators  

| Aspect | Existing Systems | **This Idea** |
|--------|------------------|----------------|
| Purpose | Focused on food recognition (what food it is) | Focused on *inside prediction* (what’s hidden inside) |
| Use Case | Utility (menu scanning, calorie detection) | Entertainment + curiosity-driven AI |
| Model Output | Label: “붕어빵” | Label: “붕어빵 — likely red bean (82%)” |

---

## ⚙️ System Architecture  
**Input:** Photo of a filled food (top or side view)  
**Process:**  
- Image preprocessing (lighting correction, shape extraction)  
- CNN-based classifier → predicts filling type  
- Visualization module → displays confidence score  
**Output:** Probabilistic guess of the filling (e.g., “🫘 Red Bean: 0.82 | 🍫 Chocolate: 0.14 | 🍠 Sweet Potato: 0.04”)  

---

## 📦 Technology Stack  
- **Backend:** FastAPI  
- **Model / AI:** ResNet18 (lightweight CNN)  
- **Frontend:** Streamlit or Gradio for quick prototyping  
- **Database:** SQLite or local JSON labeling  
- **Libraries:** PyTorch, OpenCV, Pillow, Matplotlib  

---

## 🚀 Use Cases  
- 🍞 **Food Game:** Users upload a photo and guess the filling before the AI reveals it.  
- 🍠 **AI Challenge:** Compare human vs AI guessing accuracy.  
- 📸 **Dataset Expansion:** Encourage users to upload labeled photos for community training.  

---

## 🌐 Future Extensions  
- Add **thermal camera data** or **NIR imaging** for more accurate internal predictions.  
- Expand to **non-food items** (e.g., gift boxes, surprise toys).  
- Develop a **“Guess Inside” mobile AR game** that visualizes predicted fillings in real-time.  

---

## 🧭 Vision  
> “To make AI not just see the world — but *imagine* what’s hidden inside it.”  
