# 🧠 Project Title: AI Pottery Assistant — Suggesting and Evaluating Ceramic Forms

## 🔍 Summary
AI Pottery Assistant is a design-support tool that helps potters and designers generate **diverse pottery shapes** and evaluate their **aesthetic and functional qualities**.  
It combines traditional craftsmanship with modern AI, enabling both beginners and experts to explore new forms and receive objective feedback.

---

## 🎯 Problem Statement
- Pottery design is creative but constrained by imagination and skill.  
- Beginners struggle with **balance, proportion, and stability**.  
- Experts may benefit from design augmentation or evaluation support.  
- There is no AI tool dedicated to the nuanced and organic forms of ceramics.  

**Goal:** Provide AI-driven generation and evaluation tools to assist pottery ideation and training.

---

## 📚 Background & Motivation
- Inspired by attending a pottery workshop: fun process, but results were often disappointing.  
- Realized many learners face the same challenge of form imbalance.  
- Pottery has infinite variations (bowls, vases, cups, jars), making it ideal for generative models.  
- AI design tools (GANs, DALL·E, etc.) show the potential of human–AI collaboration in art.  

---

## 📊 Potential Data Sources
- 3D pottery model datasets (Sketchfab, Thingiverse, MyMiniFactory).  
- Museum collections: The Met, British Museum, Korea Craft Museum.  
- Social media datasets (Instagram, Pinterest) for modern ceramic designs.  
- Manually annotated features: rim type, foot type, height–width ratio, curvature smoothness.  

---

## 🧪 Technical Approach
1. **Shape Generation**  
   - Variational Autoencoders (VAE) or GANs for 2D silhouettes or 3D meshes.  
   - Conditional generation based on parameters (height, style, period).  

2. **Shape Evaluation**  
   - Feature extraction (symmetry, proportions, smoothness).  
   - Train models to predict aesthetic or balance scores.  

3. **User Interface**  
   - Interactive input via Streamlit or Gradio.  
   - Sketch-to-shape functionality or parameter sliders.  
   - Blender integration for 3D previews and STL export.  

---

## 💡 Applications
- Assist potters with rapid **form ideation**.  
- Provide **feedback tools** for beginners learning aesthetics.  
- Enable co-creation between human artisans and AI.  
- Industrial applications: digital fabrication, 3D printing, ceramic product design.  

---

## ⚠️ Notes
- Requires high-quality 3D training data, which may be scarce.  
- Aesthetic evaluation is subjective → needs expert input for labeling.  
- Real-world adoption depends on usability and artist trust.  

---

## 🔗 Related Inspirations
- GAN-based product design tools.  
- Museum digital collections of ceramics.  
- Generative art platforms exploring form and function.  

---

## 🗂️ Suggested Folder Name
`creative/ai-pottery-assistant`
