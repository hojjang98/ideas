# 🧠 Project Title: **FactRank – A Publicly Curated Fact Repository**

## 🔍 Summary  
FactRank is a collaborative platform for verifying and archiving factual information. It aims to combat misinformation by assigning **credibility scores** to submitted facts, based on community input and algorithmic evaluation. Unlike open wikis, the platform emphasizes **verifiability**, **evidence tracking**, and **reputation-based fact scoring**.

## 🎯 Problem Statement  
In the age of social media, misinformation spreads faster than truth. Open platforms allow anyone to post content, but lack mechanisms to evaluate whether a piece of information is actually **true, well-evidenced, or manipulated**. There is a growing need for a system where **verifiable facts are separated from speculation**, especially in domains like health, politics, and science.

## 📚 Background & Motivation  
- Existing platforms (e.g., Wikipedia, NamuWiki) are editable but often **lack citation enforcement**  
- Search engines prioritize popularity over credibility  
- Misinformation can **affect elections, public health, and social trust**  
- Critical thinking skills are not evenly distributed across users  
- We need a **structured, crowd-verifiable fact library**

## 📊 Potential Data Sources  
- Verified news APIs (e.g., Reuters, AP, Yonhap)  
- Government open data portals  
- Research papers (e.g., Semantic Scholar, PubMed, arXiv)  
- WHO/CDC data for health-related facts  
- User-contributed facts with reference links

## 🧪 Possible Approaches  
- RLHF (Reinforcement Learning from Human Feedback)-inspired scoring of facts  
- Fact “blocks” with source, date, citation level, topic tag  
- Community voting + moderation reputation systems  
- LLM-assisted fact extraction from cited sources  
- Plausibility models trained on fact-vs-fake datasets (e.g., LIAR, Fakeddit)

## 💡 Expected Insights or Applications  
- A living repository of **trust-scored facts**, searchable by topic  
- A browser plugin that flags unverified or low-ranked claims  
- Dashboards showing **fact gaps** in hot issues (e.g., elections, pandemics)  
- A classroom or civic education tool to promote **evidence-based reasoning**

## ⚠️ Notes  
- The platform does **not aim to police opinions**, only claims labeled as **objective facts**  
- Potential challenges: brigading, coordinated disinfo attacks, overreliance on crowd  
- Needs clear fact classification: *factual*, *uncertain*, *opinion*, *speculative*

## 🔗 Related Projects / Inspirations  
- **PolitiFact**, **Snopes**, **Wikidata**, **Media Bias/Fact Check**  
- Kaggle competitions on fake news detection  
- Google’s Fact Check Explorer
