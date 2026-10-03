# AI-Powered-Text-to-SQL-Assistant
An AI-powered Text-to-SQL Assistant enabling stakeholders to query databases using plain English. Built with Python, SQLite, and the Google Gemini API, it translates natural language into optimized SQL, executes it, and outputs Pandas DataFrames. Automates ad-hoc reporting to streamline MIS and data workflows.


## 🤖 AI-Powered Text-to-SQL Business Assistant

**The Problem:** Business stakeholders often rely on Data Analysts for ad-hoc data requests, creating reporting bottlenecks and delaying data-driven decisions.

**The Solution:** This project bridges the gap between relational databases and non-technical users. Built entirely within a Jupyter Notebook, it is an interactive Text-to-SQL pipeline that allows users to ask everyday business questions in plain English and instantly receive structured insights. 

Powered by the Google Gemini Large Language Model (LLM), the application dynamically translates natural language into optimized SQL queries, executes them against a local database, and visualizes the results as clean Pandas DataFrames.

### ✨ Key Features
* **Natural Language to SQL:** Converts questions like *"Which region generated the highest electronics revenue?"* into accurate, executable code.
* **Schema-Aware Prompting:** Injects strict database constraints into the LLM to prevent syntax hallucinations and ensure reliable aggregation and filtering.
* **Resilient Architecture:** Features built-in exponential backoff algorithms to gracefully handle transient API rate limits or 503 server overloads.
* **Interactive UI:** Uses `ipywidgets` to create a seamless, self-service search bar experience directly inside the notebook environment.

### 🛠️ Tech Stack
* **Language & Environment:** Python 3, Jupyter Notebook
* **AI & NLP:** Google Gemini API (`google-genai`)
* **Database & Data Handling:** SQLite3, Pandas

### 💼 Business Impact
This tool demonstrates the practical integration of Generative AI into traditional MIS workflows. By automating repetitive ad-hoc reporting, it empowers stakeholders to access self-service analytics while freeing up the data team for deep-dive, strategic problem-solving.

---
