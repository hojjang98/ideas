# 🧠 Project Title: DanceMap — Mapping Genre-Based Dancer Hotspots in Seoul

## 🔍 Summary
DanceMap visualizes and analyzes **where dancers gather by genre** (hip-hop, waacking, popping, etc.) using online behavioral traces.  
By aggregating social and spatial signals, it builds an **interactive map of Seoul’s dance hotspots**, helping newcomers navigate the scene while supporting community-based cultural design.

---

## 🎯 Problem Statement
- New dancers often struggle to discover **where and how to start**.  
- Genre-specific hubs exist but information is fragmented and inaccessible to outsiders.  
- Current platforms show dance studios but not **community-based activity patterns**.  

**Goal:** Create a **data-driven map of dance culture** in Seoul that reflects genre-specific communities and their urban footprint.

---

## 📚 Background & Motivation
- Inspired by recent pose-estimation–based dance classification experiments.  
- Many dancers say they “found the scene by accident,” highlighting entry barriers.  
- Urban dance spaces (studios, street practice spots, clubs) are vital to cultural vibrancy but lack visibility.  
- With K-pop and shows like *스트릿 우먼 파이터* boosting popularity, demand for **localized information** is rising.  

---

## 📊 Potential Data Sources
- Instagram posts with location tags + genre hashtags (#waacking연습실, #힙합댄스).  
- Naver blogs and café posts about studios or meetups.  
- Google Maps / Kakao Map POI data + review scraping.  
- YouTube vlogs with dance practice/battle location mentions.  
- (Optional) Anonymized user-submitted location diaries.  

---

## 🧪 Technical Approach
1. **Data Collection**  
   - Crawl social posts, map APIs, and blog mentions.  
   - Extract genre–place linkages via NLP.  

2. **Spatio-Temporal Analysis**  
   - Cluster activity by time to identify bursts (e.g., battles, workshops).  
   - Score hotspots using frequency and diversity metrics.  

3. **Visualization**  
   - Build an interactive Folium or Kakao Map visualization.  
   - Color-code by genre and intensity of activity.  

4. **Extensions**  
   - Enable crowd-contributed geo-checkins.  
   - Add filters: genre, activity level, time-of-day.  

---

## 💡 Applications
- **For Dancers:** Entry guide showing where to go by genre.  
- **For Communities:** Showcase diversity across dance hubs.  
- **For Policy Makers:** Highlight under-supported cultural zones.  
- **For Researchers:** Provide data on how youth culture shapes urban spaces.  

---

## ⚠️ Notes
- Privacy must be respected — no tracking of individual movement without consent.  
- Social media data will contain noise; filtering heuristics are essential.  
- Studio addresses and events may need manual validation.  
- Framework can later expand beyond Seoul to other cities.  

---

## 🔗 Related Inspirations
- Heatmaps of street performance in urban studies.  
- Music scene mapping in NYC and Berlin.  
- Pose-based dance classification research.  
- GIS cultural equity tools used by local governments.  

---

> “Dance is not just performance — it’s geography, community, and culture.”
