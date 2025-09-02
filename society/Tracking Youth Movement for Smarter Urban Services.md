# 🧠 Project Title: Seoul Youth Footprint — Mapping Young Mobility for Smarter Urban Policy

## 🔍 Summary
Seoul Youth Footprint leverages **vehicle ownership statistics** and **voluntary location tracking** to map where young people actually spend their time.  
By uncovering youth mobility patterns, it supports **data-driven, place-based policies** that better reflect real behavioral trends instead of relying solely on demographics.

---

## 🎯 Problem Statement
- Current youth policies are often based on static **demographic data**, not **behavioral movement data**.  
- This mismatch results in public services that fail to align with youth interests or activity hubs.  
- There is no widely available tool to visualize **real-time, location-based insights** on youth mobility in Seoul.  

**Goal:** Provide policymakers with **actionable insights** into where and how young people move, helping design smarter, more relevant urban programs.

---

## 📚 Background & Motivation
- Seoul’s youth are highly mobile and diverse, yet underrepresented in urban planning decisions.  
- Inspired by analyzing vehicle ownership statistics, which showed significant car usage among youth.  
- Young residents often frequent **hidden or emerging local spots**, beyond traditional policy assumptions.  
- Understanding these patterns can **rebalance resources** and create **youth-focused initiatives**.  

---

## 📊 Potential Data Sources
- Seoul Metropolitan Government youth vehicle ownership stats (공공데이터포털).  
- KOSIS / 서울열린데이터광장 population and demographics.  
- Voluntary smartphone-based GPS tracking (with user consent).  
- Points of Interest (POI) datasets: cafes, coworking spaces, nightlife, etc.  
- Optional: telecom or card transaction data for aggregated footfall (privacy-compliant).  

---

## 🧪 Technical Approach
1. **Data Collection**  
   - Integrate public datasets + voluntary app-based GPS logs.  

2. **Hotspot Detection**  
   - Use clustering (DBSCAN, KMeans) to find youth activity clusters.  

3. **Temporal Modeling**  
   - Analyze time-based usage (weekday vs. weekend, daytime vs. nighttime).  

4. **POI Tagging**  
   - Classify hotspots by type (study, leisure, work, community).  

5. **Visualization**  
   - Build GIS dashboards or interactive maps showing youth mobility.  

---

## 💡 Applications
- Reveal **actual popular areas** among Seoul youth, beyond assumed hotspots.  
- Enable targeted program allocation (career workshops, health pop-ups, cultural events).  
- Provide **district-level insights** for responsive local government planning.  
- Expandable to other age groups or cities for broader urban mobility insights.  

---

## ⚠️ Notes
- Project prioritizes **consent and anonymization** — no continuous tracking without user permission.  
- Car ownership as a proxy may bias the sample; non-car users must be included in later phases.  
- Policy applications may vary across Seoul districts, requiring cross-agency collaboration.  

---

## 🔗 Related Inspirations
- Seoul Open Data Plaza vehicle registration datasets.  
- Google Location History–based urban mobility studies.  
- Copenhagen City Data Exchange youth activity visualization.  
- U.S. city reports on millennial migration trends.  

---

> “Design policies where youth actually live, work, and play — not just where the data says they should.”
