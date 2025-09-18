# text2sql-pipeline  
> **Natural Language → SQL Query Pipeline (Under Development)**  

This repository implements a Text-to-SQL system where users upload a CSV file, which is converted into a SQLite3 database. Natural language queries are transformed into SQL queries using **OpenAI GPT models (via API key)**, executed on the database, and the results are returned as human-readable answers.  

---

## 📌 Features  
- Upload **CSV** → automatically converted into **SQLite3 database**  
- Natural language → **SQL query** generated using **OpenAI GPT**  
- Query execution using **LangChain’s DatabaseChain & QueryChain**  
- Human-readable answers also generated via **OpenAI GPT**  
- Includes a **LangChain Agent** (experimental add-on)  
- Deployed with **Gradio** for easy interaction  

---

## 🛠 Tech Stack  
- **SQLite3** → database creation  
- **LangChain** → query execution chains & agent integration  
- **OpenAI GPT (API key)** → SQL generation + answer explanation  
- **Gradio** → deployment  

---

## 🚧 Current Limitations  
- SQL generation accuracy depends on GPT prompting and schema clarity.  
- Experimental **LangChain Agent** can be unstable and is still in progress.  
- Query handling for large/complex datasets is under development.  

---

## 🔮 Roadmap / Next Steps  
- [ ] Optimize Agent


## ⚠️ Disclaimer  
This is a **research/development project**. The system is experimental and may return incorrect or incomplete SQL queries.  
