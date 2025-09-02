# 🧠 Project Title: BodyTrack3D — Visual Body Change Tracker with Computer Vision

## 🔍 Summary
BodyTrack3D is a computer vision-based tool that tracks **upper-body muscle changes** (chest, shoulders, back) over time.  
By extracting pose-based geometric features from periodic photos, it offers **quantitative and visual feedback**, moving beyond subjective “before & after” comparisons.

---

## 🎯 Problem Statement
- Traditional “눈바디” (eye-check) is subjective and unreliable.  
- Muscle growth in chest, shoulders, and back is visually subtle and hard to measure.  
- Existing methods (weight, InBody scans) fail to capture visible shape change.  

**Goal:** Provide a **pose-aware, geometric analysis tool** that quantifies body change and supports user motivation.

---

## 📚 Background & Motivation
- Born from the question: *“Am I really making progress?”*  
- Numbers like weight or fat percentage don’t always match what people want to see: **shape change**.  
- Advances in pose estimation enable **consistent alignment and comparison** across photos.  
- Aims to give fitness users **objective, measurable, and motivating visual evidence**.

---

## 📊 Potential Data Sources
- User photos (front / side / back) collected periodically.  
- Pose estimation frameworks: **OpenPose, BlazePose, MediaPipe**.  
- Optional: **SMPL / BodyPix** for 3D body mesh approximation.

---

## 🧪 Technical Approach
1. **Pose Alignment**  
   - Standardize body posture using 2D pose estimation.  
   - Normalize size, crop, and rotate for consistency.  

2. **Feature Extraction**  
   - Key geometric metrics:  
     - Shoulder width (distance between keypoints)  
     - Chest contour (ribcage-level width)  
     - Back angle/area (trapezius spread)  
     - Arm-body angle (symmetry check)  

3. **Change Detection**  
   - Track metrics over time (weekly/monthly).  
   - Visualize changes with charts, heatmaps, or overlays.  

4. **Output Interface**  
   - Web dashboard (Streamlit/Flask):  
     - Before–after overlay  
     - Metric table & graphs  
     - Optional pseudo-3D mesh view  

---

## 💡 Applications
- **Fitness Motivation:** Show measurable progress beyond scales.  
- **Personal Training:** Support PT coaches with visual evidence.  
- **Consumer App:** Mobile-based “visual growth tracker” for gym-goers.  

---

## ⚠️ Notes
- Lighting, angle, and clothing variation may affect accuracy.  
- Requires privacy-sensitive handling of user photos.  
- Baseline calibration (e.g., fixed camera setup) is important for reliability.

---

## 🔗 Related Inspirations
- Pose-based fitness apps (AI squat/push-up counters).  
- 3D body scanning solutions for professional fitness tracking.  
- Self-tracking tools combining visual and biometric data.

---

> “Track your growth — not just your weight.”
