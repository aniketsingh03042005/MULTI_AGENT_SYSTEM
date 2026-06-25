# 🔍 Multi-Agent Research Assistant

An AI-powered Multi-Agent Research Assistant that automates web research, content extraction, report generation, and research evaluation using LangChain, Groq, Tavily, and Streamlit.

## 🚀 Overview

This project uses multiple AI agents working together to perform research tasks efficiently. The system searches the web, gathers relevant information, analyzes the content, generates a structured report, and evaluates the quality of the generated report.

The goal is to automate the research process and provide reliable, well-structured, and informative outputs.

---

## ✨ Features

* 🤖 Multi-Agent Architecture
* 🌐 Real-Time Web Search using Tavily
* 📄 Website Content Scraping
* 🧠 AI-Powered Research Analysis
* 📝 Automated Research Report Generation
* 🔍 Research Quality Evaluation
* ⚡ Groq LLM Integration
* 🎨 Interactive Streamlit Interface
* 🧩 Modular and Scalable Design

---

## 🏗️ System Workflow

User Query
↓
Search Agent
↓
Web Search (Tavily)
↓
Reader Agent
↓
Content Analysis
↓
Writer Agent
↓
Research Report
↓
Critic Agent
↓
Final Evaluated Report

---

## 🛠️ Tech Stack

| Technology     | Purpose                   |
| -------------- | ------------------------- |
| Python         | Core Programming Language |
| LangChain      | Agent Framework           |
| Groq           | Large Language Model      |
| Tavily         | Web Search API            |
| Streamlit      | User Interface            |
| BeautifulSoup4 | Web Scraping              |
| Requests       | HTTP Requests             |
| Python-dotenv  | Environment Variables     |

---

## 📂 Project Structure

Multi-Agent-System/

├── app.py

├── agents.py

├── tools.py

├── pipeline.py

├── requirements.txt

├── .env

└── README.md

---

## ⚙️ Installation

### Clone Repository

git clone https://github.com/your-username/Multi-Agent-System.git

cd Multi-Agent-System

### Create Virtual Environment

python -m venv venv

### Activate Environment

Windows:

venv\Scripts\activate

### Install Dependencies

pip install -r requirements.txt

### Configure Environment Variables

Create a `.env` file:

TAVILY_API_KEY=your_tavily_api_key

GROQ_API_KEY=your_groq_api_key

---

## ▶️ Run Application

streamlit run app.py

---

## 📊 Example Research Topics

* Artificial Intelligence in Healthcare
* Future of Quantum Computing
* Electric Vehicles in India
* Cybersecurity Trends
* Renewable Energy Technologies
* Generative AI Applications

---

## 🎯 Use Cases

* Academic Research
* Technical Research
* Industry Analysis
* Market Research
* Content Creation
* Knowledge Discovery

---

## 🔮 Future Improvements

* PDF Export
* Citation Support
* Multi-Source Verification
* Agent Memory
* RAG Integration
* Multi-LLM Support

---

## 👨‍💻 Author

**Aniket Singh**

B.Tech Computer Science Student

Passionate about Artificial Intelligence, Multi-Agent Systems, Generative AI, Machine Learning, and Software Development.

### Connect With Me

GitHub: https://github.com/aniketsingh03042005

---

⭐ If you found this project useful, please consider giving it a star on GitHub!
