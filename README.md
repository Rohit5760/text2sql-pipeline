# text2sql-pipeline  
> **Natural Language → SQL Query Pipeline (Under Development)**  

This repository implements a Text-to-SQL system where users upload a CSV file, which is converted into a SQLite3 database. Natural language queries are transformed into SQL queries using a fine-tuned LLM, executed on the database, and the results are returned as human-readable answers.  

---

## 📌 Features  
- Upload **CSV** → automatically converted into **SQLite3 database**  
- Natural language → **SQL query** using [`bugdaryan/Code-Llama-2-13B-instruct-text2sql`](https://huggingface.co/bugdaryan/Code-Llama-2-13B-instruct-text2sql)  
- Query execution using **LangChain’s DatabaseChain & QueryChain**  
- Human-readable answers generated with **Falcon (tiiuae/Falcon)**  
- Deployed with **Gradio** for easy interaction  

---

## 🛠 Tech Stack  
- **SQLite3** → database creation  
- **LangChain** → query execution chains  
- **Code-Llama** → text-to-SQL generation  
- **Falcon** → natural language answers  
- **Gradio** → deployment  

---

## 🚧 Current Limitations  
- The **Code-Llama model often returns incorrect SQL queries**, which require manual optimization.  
- Pipeline stability under varied datasets, still being improved.  
- Query chain handling is still **work in progress**.  

---

## 🔮 Roadmap / Next Steps  
- [ ] Optimize SQL generation with better prompting & post-processing  
- [ ] Improve error handling for invalid queries  

---

## ⚠️ Disclaimer  
This is a **research/development project**. The system is experimental and may return incorrect or incomplete SQL queries.  
