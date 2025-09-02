# 🧠 Project Title: Trust or Trick? — Detecting Suspicious Movie Reviews through Behavioral Signals

## 🔍 Summary
This project develops a system to detect **suspicious or manipulative movie reviews** by analyzing discrepancies between star ratings, review content, and user behavior patterns.  
It aims to flag potentially **promotional or biased reviews**, helping consumers make more informed viewing decisions.

---

## 🎯 Problem Statement
- Moviegoers are often misled by reviews that don’t match their actual experience.  
- Some reviews may be artificially inflated for promotional purposes, distorting public perception.  
- Current review platforms rely heavily on **star ratings** without verifying textual consistency or reviewer credibility.  

**Goal:** Identify and surface inconsistencies between **ratings, content, and behavior** to improve trust in movie review ecosystems.

---

## 📚 Background & Motivation
- Inspired by personal experience: a mediocre film showed **dozens of glowing reviews** despite many low ratings.  
- Raised suspicion of **review manipulation** or coordinated promotion.  
- Consumers depend heavily on reviews, making this a **transparency issue** in digital society.  
- Similar problems exist in **e-commerce and food delivery platforms**, but movies are highly reputation-driven, making manipulation impactful.

---

## 📊 Potential Data Sources
- **Naver Movie Review Dataset** (네이버 영화 리뷰 감성 데이터).  
- IMDb / Rotten Tomatoes scraped reviews.  
- Public labeled datasets (AIHub, Kaggle) for training sentiment models.  
- User metadata: account age, review frequency, rating distribution.  
- Optional: manually curated examples of verified vs. suspicious reviews.  

---

## 🧪 Technical Approach
1. **Sentiment–Rating Consistency**  
   - Train sentiment classifier → compare predicted sentiment vs. star rating.  
   - Large discrepancies flagged as suspicious.  

2. **Keyword & Textual Patterns**  
   - Detect overuse of promotional keywords (“masterpiece,” “must-watch”).  
   - Check for repeated phrases across multiple reviews.  

3. **Temporal & Behavioral Analysis**  
   - Identify bursts of similar reviews posted in short time spans.  
   - Profile reviewer behavior: only reviews one film, excessive 5-star bias, or sudden account creation.  

4. **Scoring & Visualization**  
   - Build a **Review Trust Score** using Random Forest / LightGBM / transformers.  
   - Heatmaps for rating–sentiment alignment.  
   - Graph clustering of suspicious reviewer networks.  

---

## 💡 Applications
- **Consumers:** Quick indicators of likely authentic vs. suspicious reviews.  
- **Platforms:** Tools to moderate or adjust weighting of reviews.  
- **Research:** Extend framework to other domains (e-commerce, restaurants, books).  
- **Society:** Increase transparency and trust in digital feedback systems.  

---

## ⚠️ Notes
- Not intended as a censorship tool — purely for transparency.  
- Must respect reviewer privacy (no personal data exposure).  
- “Suspicious” does not equal “fake”; false positives must be minimized.  
- Crowdsourced validation could strengthen accuracy and trust.  

---

## 🔗 Related Inspirations
- Fake review detection studies in NLP (*Deceptive Opinion Spam*).  
- Kaggle projects on Amazon review authenticity.  
- Rotten Tomatoes review scoring inconsistencies.  
- Naver 영화 후기 이상치 탐지 관련 블로그 및 연구.  

---

> “Not every five-star shines the same — let’s reveal the truth behind the ratings.”
