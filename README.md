# 🧠 AI Voice Avatar Recruiter System

The **AI Voice Avatar Recruiter** is an advanced conversational AI system that simulates real human recruiters using **LLMs** and **voice synthesis technology**. It conducts realistic, interactive voice interviews with candidates, evaluates responses, and generates structured reports — revolutionizing how organizations handle recruitment automation.

---
<img width="1810" height="985" alt="image" src="https://github.com/user-attachments/assets/f9697b83-2f76-4518-8fca-0720e93bb20b" />

## 🚀 Features

- 🎤 **AI Voice Conversations** — Conducts natural, two-way voice interviews using **ElevenLabs Voice AI**.  
- 🧩 **LLM-Powered Intelligence** — Uses GPT-based reasoning to analyze answers and ask contextual follow-up questions.  
- 📊 **Automated Evaluation** — Generates structured reports with communication, skill, and tone scoring.  
- 🌐 **Multi-Role Simulation** — Configurable recruiter personalities (HR, Technical, Managerial).  
- ☁️ **Integrations** — Connects with HR systems, CRMs, or applicant tracking tools.  
- 💬 **Multi-Language Support** — Handles interviews in multiple languages for global recruitment.

---

## 🏗️ Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Python (Flask / FastAPI) |
| **AI Model** | GPT (OpenAI API) |
| **Voice Engine** | ElevenLabs Voice AI |
| **Database** | PostgreSQL / Firebase |
| **Frontend (Optional)** | React / Flutter |
| **Automation** | n8n / Zapier Integration |

---

## ⚙️ How It Works

1. **Candidate connects** to the AI Recruiter via web or voice interface.  
2. The system **initiates a conversation**, asking HR or technical questions.  
3. Candidate responses are **analyzed in real time** using LLMs.  
4. A **summary report** is generated with key insights and recommendations.  

---

## 🧩 Architecture Overview

```
User (Voice Input)
       ↓
Speech-to-Text (STT)
       ↓
GPT-based Recruiter Logic
       ↓
Text-to-Speech (ElevenLabs)
       ↓
Voice Output + Evaluation Report
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/AI-Voice-Avatar-Recruiter.git
cd AI-Voice-Avatar-Recruiter
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables
Create a `.env` file in the root directory and add your API keys:
```bash
OPENAI_API_KEY=your_openai_key
ELEVENLABS_API_KEY=your_elevenlabs_key
```

### 4. Run the Application
```bash
python app.py
```

---

## 🧪 Example Interaction

> **AI Recruiter:** “Hi there! Could you tell me about a time you solved a challenging problem at work?”  
> **Candidate:** “Sure, I was leading a project where…”  
> **AI Recruiter:** “Interesting. What skills did you use to handle that situation?”  
>  
> *(After completion, a structured candidate evaluation report is generated.)*

---

## 📈 Future Enhancements

- 🤖 Emotion-aware voice tone detection  
- 📞 Integration with WhatsApp or phone interviews  
- 🗂️ Resume parsing and auto-question generation  
- 🧍 Personalized recruiter avatars (3D or video-based)

---

## 📄 License

This project is licensed under the **[MIT License](LICENSE)**.

---

## 👩‍💻 Author

**Maheen Meshram**  
AI Developer & Innovator  
- 🔗 [GitHub](https://github.com/yourusername)  
- 💼 [LinkedIn](https://linkedin.com/in/yourprofile)
