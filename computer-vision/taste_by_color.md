# 🧠 Project Title: **Taste by Color: Predicting Seasoning Levels from Food Images**

## 🔍 Summary  
This project explores whether the **seasoning level (under-seasoned, well-seasoned, over-seasoned)** of a dish can be inferred solely from its appearance—particularly its **color and visual texture**. Inspired by the real-world intuition of army cooks, the goal is to build a visual model that mimics human gut-feeling based on color.

---

## 🎯 Problem Statement  
- Cooking apps and recipes rarely tell you *how it should look* when seasoned properly.  
- Beginners can't tell if their food is over- or under-seasoned just by looking.  
- Human experts (like army cooks) often judge seasoning levels by color alone.  
→ Can we **train a machine to do the same?**

---

## 📚 Background & Motivation  
- Inspired by the creator’s personal experience as a military cook:  
  **“I could tell whether a dish was salty or not just by looking at the color.”**  
- Visual cues like darkness, redness, or oil sheen often correlate with flavor strength.  
- Could aid beginner cooks, automated kitchens, or food photo reviewers.

---

## 📊 Potential Data Sources  
- YouTube cooking videos + subtitles ("too salty", "a bit bland")  
- Recipe blogs with final dish photos and taste comments  
- Self-generated dataset: same recipe cooked at different seasoning levels  
- Academic papers or datasets on food image classification

---

## 🧪 Possible Approaches  
- Extract color histograms, brightness, and saturation metrics from food images  
- Train a CNN to classify images into: **under-seasoned / well-seasoned / over-seasoned**  
- Control for lighting conditions or filter out images with artificial coloring  
- Augment data using GANs to simulate variations in seasoning levels

---

## 💡 Expected Insights or Applications  
- AI assistant for home cooks: “Your stew looks a bit pale—maybe add more soy sauce.”  
- Visual cooking tutorials that *show* what the right color looks like  
- Quality control in food delivery or automated kitchens  
- Fun mobile apps that score your dish’s taste based on looks alone

---

## 🤖 Bonus Ideas  
- Connect with **text-based recipe inputs** to predict expected color vs actual result  
- Recommend adjustments: “Add 1 tsp of salt to match ideal tone.”  
- Future extension: combine with **smell/sound sensors** for multimodal flavor prediction
