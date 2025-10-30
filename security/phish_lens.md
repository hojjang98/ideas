# 🧠 Project Title: **PhishLens — Social Engineering-Aware Phishing Detection Platform**

---

## 🔍 Summary  
**PhishLens** is an AI-based phishing detection and visualization platform that goes beyond technical signatures.  
Instead of checking URLs or attachments, it analyzes **psychological manipulation patterns** inside phishing messages —  
revealing how attackers exploit human emotions like fear, urgency, and greed.  

By combining **LLM-driven affect analysis** with **social engineering linguistics**, PhishLens visualizes “how you are being manipulated”  
rather than just saying “this is a phishing message.”  

---

## 🎯 Problem Statement  
- Modern phishing has evolved from simple scams to **emotionally engineered communication**.  
- Victims fall for scams not because of lack of technical knowledge, but because of **psychological immersion**.  
- Existing systems detect malicious URLs or payloads but **ignore linguistic manipulation** that actually convinces the victim.  

---

## 💡 Key Objectives  
1. Detect **psychological manipulation tactics** in text messages, emails, or SNS chats.  
2. Classify sentences by **emotional intensity and persuasion type** (fear, urgency, authority, reward).  
3. Provide **visual explanation (heatmap)** and **educational feedback** for users.  
4. Build a **dataset of social engineering language patterns**, including LLM-generated scams.  

---

## 🧩 Core Differentiators  

| Aspect | Existing Systems | **PhishLens** |
|--------|------------------|----------------|
| Detection Target | URL, domain, attachments | **Text-based emotional manipulation** |
| Technology | Blacklist & signature matching | **LLM + Emotion Analysis + Linguistic Pattern Mining** |
| Result Type | Binary risk label (safe/dangerous) | **Explainable visualization (sentence-level heatmap)** |
| Focus | Technical behavior | **Human psychological vulnerability** |
| Use Case | Enterprise email filtering | **User education, awareness, and cyber psychology research** |

---

## ⚙️ System Architecture  

**Input:** Text (SMS, email body, chat log)  
**Processing Pipeline:**  
1. **Preprocessing** — Tokenization, stopword removal  
2. **Emotion Classification** — KoELECTRA / BERT-based affect model  
3. **Social Engineering Pattern Matching** — Pattern DB (fear, urgency, authority, reward, sympathy)  
4. **LLM Reasoning Layer** — Contextual scoring & explanation  
5. **Visualization Layer** — Sentence-level heatmap + risk summary  

**Output:**  
- Risk visualization (color map of emotional manipulation)  
- Attack tactic classification  
- Explainable feedback  

---

## 📦 Technology Stack  
- **Backend:** FastAPI / Flask  
- **Model:** KoBERT, KoELECTRA, or fine-tuned LLM  
- **Frontend:** Streamlit or Dash for real-time visualization  
- **Database:** SQLite / MongoDB for message & tactic logs  
- **Libraries:** HuggingFace Transformers, Plotly, spaCy  

---

## 🚀 Use Cases  
- **Cybersecurity Awareness Training**  
  → Visual phishing education for companies and schools  
- **Threat Intelligence Research**  
  → Collect and categorize real-world phishing text tactics  
- **AI-generated Scam Detection**  
  → Identify LLM-produced phishing narratives  
- **User-facing Browser Plugin**  
  → Inline visualization of suspicious messages  

---

## 🌐 Future Extensions  
- Integrate with browser/email clients for live phishing warnings  
- Expand multilingual support (Korean, English, Chinese)  
- Cross-reference with real phishing databases (KISA, VirusTotal)  
- Introduce adaptive feedback loop to teach users how to spot emotional triggers  

---

## 🧭 Vision  
> PhishLens shifts cybersecurity from **“technical threat blocking”**  
> to **“human-centered awareness and understanding.”**  
It aims to make users not just protected — but **psychologically resilient** against modern phishing.

---
