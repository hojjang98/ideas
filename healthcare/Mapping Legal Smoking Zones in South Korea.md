# 🧠 Project Title: Mapping Legal Smoking Zones in South Korea

## 🔍 Summary
This project visualizes and analyzes **legally designated smoking areas** across South Korea using GIS.  
It investigates the **gap between smoking restrictions and available legal zones**, emphasizing **urban accessibility** and **spatial justice** for smokers.

---

## 🎯 Problem Statement
- “No Smoking” signs are ubiquitous, yet it is often unclear **where smoking is legally allowed**.  
- Arbitrary or unofficial stickers create confusion and limit compliance.  
- Smokers face practical challenges in finding legal areas, while non-smokers demand safe environments.  

**Goal:** Map and analyze smoking zones to clarify regulations and assess urban accessibility.

---

## 📚 Background & Motivation
- Non-smoking zones have rapidly expanded since the 2010s.  
- Government policies reduce second-hand smoke but provide few designated alternatives.  
- Smokers frequently report difficulty finding legal smoking areas.  
- Potential spatial bias: some neighborhoods may have **no legal zones at all**.  
- The project does not promote smoking; instead, it focuses on **policy transparency and fairness**.  

---

## 📊 Potential Data Sources
- Seoul Open Data Plaza: official smoking area datasets.  
- Ministry of Environment / MOLIT geospatial data.  
- Complaint records on smoking violations (e.g., 120 Dasan Call Center).  
- Government open data portals listing non-smoking zones.  
- Crawled map data from Kakao/Daum/Naver.  
- Field surveys or user-submitted data (future crowdsourced mapping).  

---

## 🧪 Technical Approach
1. **GIS Visualization**  
   - Map smoking zones vs. non-smoking zones, highlight density differences.  

2. **Spatial Analysis**  
   - Calculate accessibility metrics (nearest distance, average distance).  
   - Identify neighborhoods lacking legal zones.  

3. **Policy Review**  
   - Compare regional smoking policies and enforcement practices.  

4. **Community Feedback**  
   - Collect opinions from forums/social media on usability of existing smoking zones.  

5. **Optimization**  
   - Suggest optimal smoking zone placements based on traffic and population density.  

---

## 💡 Applications
- Reveal **urban blind spots** with no legal smoking options.  
- Prototype a **“Where to Smoke” app** for public use.  
- Provide evidence-based recommendations for local governments.  
- Contribute to debates on balancing non-smoker rights and smoker accessibility.  
- Collaborate with urban planners or public health researchers.  

---

## ⚠️ Notes
- Regional differences (district-level laws) must be accounted for.  
- Crowdsourced mapping could improve scalability and real-world accuracy.  
- Sensitive policy context: project should remain **neutral and analytical**.  

---

## 🔗 Related Inspirations
- “SmokeMap” (pilot project in Japan).  
- Seoul’s Non-Smoking Zone Ordinances.  
- U.S. “WhereToSmoke” app.  

---

## ✅ Implementation
GitHub Repository: [hojjang98/Misc-Projects – seoul-smoking-gis](https://github.com/hojjang98/Misc-Projects/tree/main/seoul-smoking-gis)  
Implemented using **Folium**, **Pandas**, and **public GIS data** for Yongsan-gu and Yeongdeungpo-gu in Seoul.  
The repository includes:  
- Smoking zone mapping scripts.  
- Distance and accessibility analysis.  
- Initial visualization results for selected districts.  
