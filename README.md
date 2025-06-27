# agentic-multigrade-ai

# 🎓 EmpowerEd: AI Agents for Multi-Grade Classrooms

Welcome to **EmpowerEd**, a project submitted for the **Google Cloud Agentic AI Day Hackathon** by Team _This_is_the_Way_.  
Our mission: **Empower teachers** in multi-grade classrooms with **AI-powered agentic tools** to enhance personalized learning in under-resourced settings.

---

## 🚀 Problem Statement

In many rural and under-resourced areas, one teacher manages multiple grades in a single classroom.  
This makes it difficult to offer **individualized attention**, leading to disengagement and learning gaps.

---

## 💡 Our Solution

We present a **multi-agent AI system** that:
- 🧠 **Assesses** student levels dynamically  
- 📚 **Generates grade-specific lesson plans**  
- 🗣️ **Interacts** with students in regional languages  
- 🤖 **Handles queries and quizzes** autonomously  
- 🧑‍🏫 **Supports teachers as facilitators** rather than content deliverers

---

## 🧱 Tech Stack

| 🔧 Tool/Tech               | 🌐 Purpose                                      |
|---------------------------|------------------------------------------------|
| **Google Cloud**          | Core infrastructure (Compute, Firebase, BQ)    |
| **Vertex AI / Gemini**    | Content generation + student understanding     |
| **LangChain / CrewAI**    | Multi-agent orchestration                      |
| **Dialogflow CX**         | Voice/chatbot support in local languages       |
| **Classroom, Sheets, Slides API** | Grade-wise content delivery         |
| **MediaPipe / Teachable Machine** | Gesture-based input in offline mode  |

---

## 🧠 AI Agent Roles

| Agent        | Role Description                                        |
|--------------|---------------------------------------------------------|
| 🎯 Goal Setter   | Understands learning goals from teachers/students     |
| 🧪 Assessor      | Gauges student proficiency level                      |
| 📖 Planner       | Designs real-time, multi-grade lesson plans          |
| 👩‍🏫 Facilitator   | Answers doubts, manages tasks                        |
| 📊 Evaluator     | Generates quizzes and tracks performance              |

---

## 🌍 Impact

✅ Personalized education in resource-limited settings  
✅ Reduced teacher burden, improved student outcomes  
✅ Scalable to multiple states and languages  
✅ Aligned with India's rural education goals

---

## 🛠️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/your-user/empower-ed.git

# Change directory
cd empower-ed

# Install dependencies (example: Node + Python)
npm install
pip install -r requirements.txt

# Start local server / agents
npm start
python main.py
