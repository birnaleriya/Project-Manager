<<<<<<< HEAD
# Project-Manager
=======
# 🤖 AI-Powered Project Management Using AI Agents with Streamlit + Airtable

This project is an AI-powered Project Management assistant built using **Streamlit**, integrated with **Airtable** for data storage. It leverages modular AI agents to generate tasks, allocate them, assess risks, and generate actionable insights.

---

## 🚀 Features

- 📋 Upload a CSV file of team members and skills
- 🤖 AI-based task generation from project description
- 🧩 Task dependency detection and scheduling
- 👥 Smart task allocation based on team member skills
- ⚠️ Risk assessment and insight generation
- 📊 Syncs all updates to **Airtable**
- 🔄 Export final structured output as CSV
- ✅ Integrated CI pipeline using GitHub Actions

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/ManideepMuddagowni/Project-Manager-AI-Agents-Assistant.git
cd ai-project-manager
```

### 2. Create virtual environment and install dependencies

```bash
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows

pip install -r requirements.txt
```

---

## 🧪 Run the App Locally

```bash
streamlit run app/main.py
```

---

## 📤 Airtable Setup

Add your Airtable API key and Base ID in a `.env` file:

```env
AIRTABLE_API_KEY=your_airtable_api_key
AIRTABLE_BASE_ID=your_airtable_base_id
```

> Or add them as **secrets** in the Streamlit Cloud app dashboard.


---

## 📊 Deployment

### Option 1: **[Streamlit Community Cloud](https://streamlit.io/cloud)**

- Connect your GitHub repo
- Set `app/main.py` as the main script
- Add required secrets via the dashboard

### Option 2: Self-hosted / Docker (optional)

*Coming soon – Dockerfile support.*

---

## ✅ Sample CSV Format

```csv
Name,Profile Description
Alice,Python, ML, AI
Bob,Project Management, Scrum
```

---

## 🙌 Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Airtable](https://airtable.com/)
- [LangChain Agents / LLMs]
- [OpenAI / Groq (used)]

---

## 📄 License

MIT License – feel free to fork and customize.
>>>>>>> b7f7a5d (readme)
