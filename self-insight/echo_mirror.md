# 🧠 Project Title  
**EchoMirror: Reveal Your Hidden Language Habits with AI**

---

## 🔍 Summary  
This project creates a personal AI assistant that analyzes your written or spoken language to uncover unconscious verbal patterns. It acts like a mirror to reflect back the phrases, tones, or structures you tend to use—helping you become more aware of your communication style and potentially improve it.

---

## 🎯 Problem Statement  
People often wonder:  
> “Do I say ‘actually’ too much?”  
> “Why do I sound passive or indirect?”  
> “What kind of emotion does my writing give off?”

Yet, we don’t have easy tools to analyze our **own language habits**, especially over time. Existing writing tools focus on grammar and tone correction, but not on revealing **how we habitually express ourselves**.

---

## 📚 Background & Motivation  
- Inspired by a personal question: *“What are my unconscious speech/writing patterns?”*  
- Many people are unaware of repetitive words, filler phrases, passive tone, or even self-doubt signals.  
- Language habits can reflect confidence, emotional state, social stance, and even personality traits.  
- Tools like Grammarly help polish language, but don’t explain *why we sound the way we do*.  
→ Let’s build an AI that **learns “you” over time** and provides **linguistic self-awareness**.

---

## 🔧 Core Features  
### 1. 🧩 Personal Language Fingerprint  
- Extract most frequent words/phrases/grammatical structures from your writings (e.g., emails, journals, chats)  
- Cluster them by category: filler, hedging, intensifiers, passive constructions, etc.

### 2. 📈 Periodic Habit Feedback  
- Weekly or monthly reports: “This week, you used ‘I guess’ 12 times. That’s 30% more than last week.”  
- Graphs showing how usage changes over time.

### 3. 🧠 Emotion + Confidence Meter  
- NLP sentiment and certainty scoring for your texts: e.g., “Your language is 80% confident, 15% unsure.”  
- Track emotional tone trends: “You sounded more stressed this week.”

### 4. 🔍 Contextual Insights  
- Highlight usage patterns by topic:  
  “In work emails, you tend to be more formal but overuse passive verbs.”  
  “In journaling, you use lots of intensifiers like ‘so’, ‘very’, ‘really’.”

### 5. 🎯 Behavior Nudges  
- Subtle suggestions: “You often use ‘just’ as a softener. Would you like to explore alternatives?”  
- Or let users *intentionally keep* those habits for self-expression—no hard judgment.

---

## 📊 Potential Data Sources  
- Your own writing: diary, Notion, blog, Substack, Kakao/Telegram exports  
- (Optional) Voice input transcripts  
- Use pre-trained models like BERT, spaCy, LIWC dictionaries for NLP tagging  
- Privacy-safe local storage or self-hosted option

---

## 🧪 Possible Approaches  
- Tokenize texts → extract n-grams → POS tagging → syntax tree parsing  
- Build habit dictionary: filler, passive, hedge, etc.  
- Use unsupervised clustering + temporal trend analysis  
- Optional LLM-based summarizer for "your style"  
  (“You tend to express hesitation with ‘maybe’, ‘somewhat’, and ‘not sure’”)

---

## 💡 Expected Insights or Applications  
- Boost self-awareness of communication habits  
- Improve clarity, assertiveness, or emotional tone  
- Fun & useful for creators, speakers, therapists, job interviewees  
- Could evolve into a *personal LLM fine-tuner* someday  
- Helpful for multilingual learners noticing habits in Korean, English, etc.

---

