# 🤖 Multi AI Agent Systems with CrewAI

a professional-grade implementation of AI agents tailored for various business use cases. This system showcases how multiple agents can collaborate to solve real-world problems across industries like finance, customer service, recruitment, research, event management, and outreach.

---

## 📸 

![Screenshot 2025-04-12 012924](https://github.com/user-attachments/assets/0430626c-ba09-4fa3-bb95-b042e822df59)



---

## 🧠 AI Agent Systems

This project contains 6 specialized CrewAI agent systems:

### 1. 📊 Collaboration Financial Analysis
- Agents collaborate to perform financial data analysis, generate insights, and deliver reports.
- Use case: CFO dashboards, investment evaluations, profit-loss assessments.

### 2. 💬 Customer Support
- AI agents handle support tickets, FAQs, escalation routing, and human-like customer interactions.
- Use case: AI-enhanced live support for businesses.

### 3. 📝 Job Application Crew
- Automates resume screening, job matching, and applicant scoring.
- Use case: Recruitment and HR automation.

### 4. 📰 Research & Article Writing
- Multi-agent setup for researching a topic, summarizing key insights, and writing professional articles.
- Use case: Blogging, journalism, academic writing, SEO content.

### 5. 📅 Event Planning Tasks
- Agents collaborate to plan and schedule events, manage vendors, budget, and communications.
- Use case: Personal assistant, wedding planner, corporate event organization.

### 6. 📣 Tools for Customer Outreach
- Agents generate personalized messages, run outreach campaigns, and track responses.
- Use case: Marketing, client retention, email campaigns.

---

## 🛠️ Tech Stack

- **CrewAI**: Multi-agent orchestration
- **Python 3.10+**
- **LangChain / LLM integration**
- **OpenAI / other LLM providers**

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/multi-ai-agent-system.git
cd multi-ai-agent-system
```

### 2. Set up your virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

Create a `.env` file with the following:

```env
OPENAI_API_KEY=your_openai_key_here
```

### 5. Run an agent system

Each use case is in its own folder, e.g., to run the customer support crew:

```bash
cd customer_support
python main.py
```

---

## 📂 Project Structure

```
multi-ai-agent-system/
│
├── collaboration_financial_analysis/
├── customer_support/
├── job_application_crew/
├── research_write_article/
├── tasks_event_planning/
├── tools_customer_outreach/
├── requirements.txt
├── README.md
└── .env
```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first.

---

