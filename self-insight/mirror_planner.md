# 🧠 Project Title: **MirrorPlanner — Write Your Day, Reflect Your Growth**

## 🔍 Summary  
MirrorPlanner is a **smart mirror for self-development** that integrates handwriting recognition with IoT scheduling.  
By allowing users to **write directly on the mirror surface**, it transforms daily planning, affirmations, and reminders into a unified self-coaching experience.  
The mirror recognizes written text, converts it into actionable tasks, and provides real-time feedback — making reflection both literal and productive.  

---

## 🎯 Problem Statement  
- People often manage plans and affirmations separately across notebooks, whiteboards, and digital tools.  
- Existing smart mirrors only display data (time, weather, calendar) rather than reinforcing **behavioral habits**.  
- Users lack an environment that connects **writing, reflection, and execution** in one seamless loop.  

**Goal:** Transform the mirror into a **personal development interface** — where writing intentions becomes the starting point for daily action.  

---

## 📚 Background & Motivation  
- Studies show that **handwriting goals** enhances focus and memory retention compared to typing.  
- The mirror, traditionally a tool for self-recognition, can become a medium for **self-direction**.  
- Combining writing and reflection creates a tangible feedback loop that strengthens **habit consistency** and **self-awareness**.  

---

## ⚙️ Key Features  
1. **Smart Writing Input** – Users write plans or affirmations directly on the mirror surface using a stylus or smart pen.  
2. **Goal-to-Action Conversion** – The system detects intent (e.g., “Exercise 9AM”) and automatically syncs with a digital scheduler or reminder system.  
3. **Interactive Overlay** – Written tasks are visually overlaid with completion icons (✔, ⏰, 🔁) and can be checked off via touch or gesture.  
4. **Routine & Reminder Engine** – Frequently written patterns (e.g., “Meditation”, “Reading”) trigger adaptive reminders or SAVERS-based habit prompts.  
5. **Weekly Reflection Dashboard** – Summarizes completed tasks, recurring goals, and consistency metrics over time.  

---

## 🧩 Technical Overview  
| Function | Technology | Description |
|-----------|-------------|-------------|
| Handwriting Recognition | Google Vision / MyScript / PaddleOCR | Converts mirror writings into text |
| Intent Parsing | spaCy / OpenAI API | Extracts action items and time expressions |
| Scheduling Integration | Google Calendar / Notion API | Automatically registers tasks and reminders |
| Display & Control | Transparent OLED + Raspberry Pi | Interactive mirror surface |
| Gesture Recognition | MediaPipe Hands | Enables non-touch control (e.g., check or erase) |

---

## 🌱 Value Proposition  
- **Bridges reflection and action** — writing becomes the first step of doing.  
- **Reinforces self-discipline** through physical engagement and visual accountability.  
- **Enhances daily structure** with minimal friction — no apps, no distractions, just your mirror.  
- Encourages **consistent SAVERS routines** by embedding affirmations and planning into the start of each day.  

---

## 🚀 Potential Impact  
- Empowers individuals to **build intentional daily habits** through tactile interaction.  
- Reduces dependency on fragmented productivity tools.  
- Creates a new category of **“reflective productivity interfaces”** for homes, studios, and workplaces.  
