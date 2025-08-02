# 🧠 Project Title:  
**AI Pottery Assistant: Suggesting and Evaluating Ceramic Forms**

---

## 🔍 Summary  
This project aims to assist potters and designers by using AI to **generate diverse pottery shapes** based on sketches or parameters, and provide **aesthetic or functional evaluations** of the forms. It bridges traditional ceramics with modern generative design tools.

---

## 🎯 Problem Statement  
Pottery design is highly creative but often constrained by the artist’s immediate imagination or technique. Beginners struggle with form ideation, while experts may benefit from design augmentation or objective evaluation tools. There is a lack of AI tools specifically tailored for the nuanced and organic world of ceramics.

---

## 📚 Background & Motivation  
- Recently experienced a **hands-on pottery workshop** and found it both exciting and frustrating — the clay work was fun, but the final result was… disappointing 😅  
- Realized that many beginners face the same challenges in **form balance, proportion, and stability**.  
- Inspired by AI-generated design tools (like GANs and DALL·E), thought: _What if AI could assist in pottery ideation and feedback?_  
- Pottery has infinite variations in form—jars, bowls, cups, vases—making it a rich design domain for generative models.  
- Many potters, both beginners and experts, could benefit from form exploration and evaluation support.

---

## 📊 Potential Data Sources  
- 3D pottery model datasets (e.g., Sketchfab, Thingiverse, MyMiniFactory)  
- Image-based ceramic datasets from museums (e.g., The Met, British Museum, Korea Craft Museum)  
- User-generated content from Instagram or Pinterest (optional)  
- Manual annotation for shape features (rim, foot, height/width ratio, curve smoothness)

---

## 🧪 Possible Approaches  
- **Shape Generation**  
  - Use VAE (Variational Autoencoder) or GANs to generate new forms in 2D silhouettes or 3D mesh  
  - Conditional generation based on parameters (e.g., height, style, time period)

- **Shape Evaluation**  
  - Extract features (symmetry, smoothness, proportions) using image processing or 3D analysis  
  - Train models to predict "balance" or aesthetic rating from expert-labeled data  

- **Interface**  
  - Use Streamlit or Gradio to allow interactive sketch input or slider-based form generation  
  - Optional: Blender integration for 3D shape preview and STL export  

---

## 💡 Expected Insights or Applications  
- Tool for potters to explore design variations quickly  
- AI-based feedback for beginners learning shape aesthetics  
- Novel collaborative model between human craftsmanship and machine creativity  
- Potential use in industrial ceramic design or digital fabrication (e.g., 3D printing)

---

## 🗂️ Suggested Folder Name  
`creative/ai-pottery-assistant`
