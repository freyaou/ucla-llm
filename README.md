# 🤖 Automated Event Planning System

This repository contains files for our **UCLA Anderson LLM Course Group Project**.

---

## 🧠 Project Overview  

Our project is a **multi-agent AI system** that transforms an idea for a company gathering into a fully scheduled event — from venue selection and timing to RSVPs and calendar invites — all in just minutes.  

Most companies still rely on multiple disconnected tools for event planning: searching venues on Yelp, sending Google Forms for RSVPs, and manually drafting calendar invites.  
Our system unifies all these steps into a single automated workflow powered by large language models.

---

## ⚙️ System Architecture  

The system orchestrates **six LLM-driven agents** built with **n8n**, **Supabase**, and **OpenRouter APIs**, each responsible for a specific part of the event-planning process:

| Agent | Function |
|-------|-----------|
| 🧭 **Event Launcher Agent** | Initializes new events and logs them into the Supabase database. |
| 📍 **Venue Brainstorming Agent** | Finds and confirms suitable locations. |
| ⏰ **Time Settler Agent** | Helps finalize optimal schedules. |
| 🏢 **Department Agent** | Identifies which departments or attendees should be invited. |
| 📋 **Questionnaire Generator Agent** | Creates and distributes RSVP forms via Google Forms. |
| 📨 **Invite Agent** | Sends calendar invites and final confirmations automatically. |

---

## 🧩 Tech Stack  

| Component | Technology |
|------------|-------------|
| **Automation Engine** | n8n |
| **Database** | Supabase PostgreSQL |
| **Language Models** | OpenRouter API |
| **Integrations** | Google Forms · Google Sheets · Gmail · Google Calendar |
| **Workflow Visualization** | Lovable.dev |
| **Demo** | Linked video below |

---

## 🗂 Repository Structure  

event-planning-system/
├── README.md
├── workflow/
│ ├── event_workflow.json # Exported n8n workflow
│ └── workflow_diagram.png # Visual of agent flow (optional)
├── docs/
│ ├── lovable_page.png # Screenshot of Lovable interface
│ └── architecture_overview.png
└── media/
└── demo_video.mp4 # Demo video file or external link

---

## 🎥 Demo  

📺 **[Watch the Demo Video](https://www.linkedin.com/feed/update/urn:li:activity:7387350514163793920?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A7387350514163793920%29&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BLUC8xGIXSNuc2KmPfnGW1w%3D%3D)**  
> The demo showcases both the user-facing flow on Lovable and the automation workflow running in n8n.

---

## 🌐 Live Workflow  

🔗 **[View the Lovable Page](https://event-guardian-angel.lovable.app/)**  

---

## 🚀 Key Features  
- Fully automated, multi-agent workflow for event planning.  
- Real-time coordination through Supabase and Google APIs.  
- Modular design for scalability and debugging.  
- LLM-driven reasoning for venue, timing, and participant selection.  

---

## 👥 Group Members  

- **Chuyi (Cheryl) Chen**  
- **Emily Oh**  
- **Freya Ou**  
- **Voravimol (Ivy) Ratanatharathorn**  
- **Yuanhang (Charles) Zhang**

---

## 🏷️ Keywords  
`#AgenticAI` · `#Automation` · `#n8n` · `#Supabase` · `#OpenRouter` · `#MultiAgentSystems`

---

## 💡 Future Work  
- Integrate adaptive feedback loops for improved scheduling and venue scoring.  
- Add Slack/Teams notifications for company-wide coordination.  
- Develop a web dashboard for real-time monitoring of workflow executions.  
