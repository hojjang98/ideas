# 🧠 Project Title: FactRank — A Publicly Curated Fact Repository

## 🔍 Summary
FactRank is a collaborative platform designed to **verify and archive factual information**.  
It assigns **credibility scores** to submitted facts through community input and algorithmic evaluation.  
Unlike open wikis, FactRank emphasizes **verifiability, citation tracking, and reputation-based scoring**, aiming to combat misinformation in domains like politics, health, and science.

---

## 🎯 Problem Statement
- Misinformation spreads faster than truth, amplified by social media algorithms.  
- Open platforms (e.g., wikis) allow contributions but often lack **robust citation enforcement**.  
- Search engines rank content by popularity, not credibility.  
- The public lacks equal access to critical evaluation skills.  

**Goal:** Build a **structured, verifiable fact library** that separates **objective facts** from speculation or opinion.

---

## 📚 Background & Motivation
- Wikipedia and NamuWiki are valuable, but citation rigor varies.  
- Fact-checking websites (e.g., PolitiFact, Snopes) exist, but lack **scalability and crowd engagement**.  
- False claims have affected elections, pandemics, and public trust.  
- FactRank proposes a **crowd-curated yet algorithmically supported fact repository** to restore credibility.

---

## 📊 Potential Data Sources
- Verified news APIs (Reuters, AP, Yonhap).  
- Government open data portals.  
- Academic repositories (Semantic Scholar, PubMed, arXiv).  
- WHO/CDC data for health-related claims.  
- User-submitted facts with mandatory source links.  

---

## 🧪 Technical Approach
1. **Fact Structuring**  
   - Facts stored as “blocks” with source, date, citation level, and topic tags.  

2. **Scoring System**  
   - Community voting + reputation-based weighting.  
   - RLHF-inspired reinforcement: reward well-sourced contributions.  

3. **Algorithmic Support**  
   - LLM-assisted fact extraction and citation verification.  
   - Plausibility models trained on fake-news datasets (LIAR, Fakeddit).  

4. **Moderation & Transparency**  
   - Fact classification: *factual*, *uncertain*, *opinion*, *speculative*.  
   - Public audit trail of evidence and edits.  

---

## 💡 Applications
- **Consumers:** Searchable library of credibility-ranked facts.  
- **Media:** Browser plugin that flags unverified or low-ranked claims.  
- **Policy & Education:** Dashboards for fact gaps in public debates.  
- **Classrooms:** Teaching tool for evidence-based reasoning.  

---

## ⚠️ Notes
- FactRank does **not police opinions** — only objective factual claims.  
- Risks: brigading, disinformation attacks, overreliance on crowds.  
- Needs robust governance and bias mitigation.  

---

## 🔗 Related Inspirations
- Fact-checking platforms: **PolitiFact**, **Snopes**, **Media Bias/Fact Check**.  
- Structured knowledge bases: **Wikidata**.  
- Kaggle fake news detection challenges.  
- Google’s **Fact Check Explorer**.  

---

> “Not just opinions — a public library of verifiable facts.”
