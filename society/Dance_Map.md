# 🧠 Project Title  
**DanceMap: Mapping Genre-Based Dancer Hotspots in Seoul**

---

## 🔍 Summary  
This project aims to visualize and analyze where dancers gather by genre (e.g., hip-hop, waacking, popping) using online behavioral traces. By aggregating social and spatial signals, it creates an interactive map that helps new dancers navigate the scene and supports community-based urban culture design.

---

## 🎯 Problem Statement  
Newcomers to dance often struggle to find where and how to start. Dance genres have distinct community hubs, but information is fragmented and often inaccessible to outsiders. There is no data-driven platform that maps physical spaces based on dancer genre or activity patterns.

---

## 📚 Background & Motivation  
- Inspired by recent pose-estimation-based dance classification experiments  
- Many dancers report they “found the scene by accident”  
- Urban dance spaces (studios, street spots, etc.) are key to cultural vibrancy but lack visibility  
- As dance grows in popularity (e.g., “스트릿 우먼 파이터”, K-pop influence), demand for entry points and localized info increases

---

## 📊 Potential Data Sources  
- Instagram location-tagged posts with genre-specific hashtags (e.g., #waacking연습실, #힙합댄스)  
- Naver blogs and café posts mentioning studios or meetups  
- Google Maps / Kakao Map POI data with custom review scraping  
- YouTube dance vlog location mentions (with transcript or description mining)  
- Optional: user-submitted dancer location diaries (anonymized)

---

## 🧪 Possible Approaches  
- NLP keyword extraction for genre-place linkage  
- Temporal clustering of content to find activity bursts (e.g., event nights, battles)  
- Geospatial visualization using Folium or Kakao Map API  
- Genre-based hotspot scoring using frequency and diversity metrics  
- Future option: crowd-contributed geo-checkins with feedback loop

---

## 💡 Expected Insights or Applications  
- Help beginner dancers find **where to go by genre**  
- Provide a **dynamic view of Seoul’s street/studio dance culture**  
- Offer insights to urban policy planners on under-supported cultural hubs  
- Support cultural equity by **highlighting less-visible dance communities**

---

## ⚠️ Notes  
- Respect privacy — no personal movement data tracked without consent  
- Some location data (e.g., studio addresses) may require validation  
- High noise expected in social media data; requires filtering heuristics  
- Could expand beyond Seoul to other cities with growing dance scenes

---

## 🔗 Related Projects / Inspirations  
- Street performance heatmaps in urban studies  
- Music scene mapping in NYC and Berlin  
- Pose-based dance classification research  
- Cultural equity GIS tools for local governments
