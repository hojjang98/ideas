# 🧠 Project Title: BodyTrack3D — Visual Body Change Tracker with Computer Vision

## 🔍 Summary  
BodyTrack3D is a computer vision-based tool that tracks **subtle upper-body muscle changes** over time (e.g., chest expansion, back width, shoulder broadening).  
By extracting pose-based geometric features from periodic photos, it provides **quantitative visual feedback** to fitness users beyond subjective "before & after" comparisons.

---

## 🎯 Problem Statement  
- Traditional “eye-check” (눈바디) is subjective and inconsistent  
- Muscle growth in areas like **chest, shoulders, and back** is hard to quantify visually  
- Users often feel uncertain about progress, leading to **loss of motivation**  
→ A structured, pose-aware, geometric analysis tool can fill this gap

---

## 📚 Background & Motivation  
- Inspired by personal frustration: “Am I really growing?”  
- Current solutions (weight, InBody scans) don’t capture visible shape change  
- Pose estimation enables consistent alignment and measurement  
- Aim to provide **objective, visual, and measurable** feedback over time

---

## 📊 Potential Data Sources  
- User-captured photos (front / side / back) on a regular basis  
- OpenPose / BlazePose / MediaPipe for 2D keypoint estimation  
- Optional: SMPL or BodyPix for 3D mesh approximation  

---

## ⚙️ Technical Approach  

### 1. **Pose Alignment**
- Use 2D pose estimation to ensure consistent body posture
- Normalize image size, crop and rotate to standard alignment

### 2. **Feature Extraction**
- Key metrics from skeleton:
  - Shoulder width (distance between keypoints)
  - Chest contour (horizontal width at upper ribs)
  - Back shape (angle or area of trapezius region)
  - Arm-body angle (for postural feedback)

### 3. **Change Detection**
- Track metric changes over time (weekly/monthly)
- Visualize with line charts, heatmaps, or morph overlays

### 4. **Output Interface**
- Streamlit / Web Dashboard with:
  - Before–after overlay
  - Metric table and graphs
  - Optional “3D-like” view via mesh approximation

---

## 🧪 Possible Extensions  
- Integrate with **mobile camera** or mirror for real-time feedback  
- Add **pose feedback** (e.g., symmetry warnings)  
- Connect with wearable data (heart rate, calorie burn) for multi-modal analysis

---

## 💡 Expected Outcomes  
- Objective evidence of visual changes in physique  
- Boost in motivation for fitness users  
- Applications for personal fitness tracking, home training apps, or PT coaches  

---

> “Track your growth — not just your weight.”
