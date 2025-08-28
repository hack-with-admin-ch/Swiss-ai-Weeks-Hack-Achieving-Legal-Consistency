 _    _                                     _    _                  _      _                     _   
| |  | |                                   | |  | |                | |    (_)                   | |  
| |__| |   __ _   _ __    _ __    _   _    | |__| |   __ _    ___  | | __  _   _ __     __ _    | |  
|  __  |  / _` | | '_ \  | '_ \  | | | |   |  __  |  / _` |  / __| | |/ / | | | '_ \   / _` |   | |  
| |  | | | (_| | | |_) | | |_) | | |_| |   | |  | | | (_| | | (__  |   <  | | | | | | | (_| |   |_|  
|_|  |_|  \__,_| | .__/  | .__/   \__, |   |_|  |_|  \__,_|  \___| |_|\_\ |_| |_| |_|  \__, |   (_)  
                 | |     | |       __/ |                                                __/ |        
                 |_|     |_|      |___/                                                |___/         
Shape the future of AI & Law – build trust into every answer! ⚖️🤖🚀


## Welcome Hackers 🚀
We’re excited to have you here for **Challenge: Achieving Legal Consistency – Swiss Law RAG (Gov2)**.  
This is your opportunity to make AI answers **legally reliable** and bring real-world impact to the Swiss Federal Administration.  

---

## The Challenge
AI assistants are powerful—but in law, **accuracy and trust** are non-negotiable.  
Your mission: build a solution that guarantees AI-generated answers are always grounded in **Swiss federal legislation**.  

Today, our in-house AI Assistnat (Based on https://github.com/open-webui/open-webui )    already runs a hybrid RAG pipeline (BM25 + embeddings + re-ranking). It’s good—but not yet robust enough for the scale and complexity of Swiss law. To move from “good” to “trusted”, we need **richer knowledge representations, explainable answers, and rock-solid grounding in the official legal corpus**.  

Your goal is to deliver:  
- **Reliable, explainable answers** to legal questions.  
- **Citations to Swiss law** for every response.  
- **Transparency via confidence scores or reasoning steps.**  

---

## Possible Approaches
- **GraphRAG**: use the provided RDF of Swiss law to generate a knowledge graph and run GraphRAG for retrieval + reasoning.  
- **Law Agent**: implement an agent that answers questions on Swiss law with confidence scores and source citations.  
- **Hybrid solutions**: combine embeddings, rules, or symbolic reasoning—surprise us!  

---

## Support for Hackers
- **Data**: Full corpus of Swiss federal legislation is provided (SPARQL endpoint + HTML assets).  
- **Mentoring**: FOITT AI team on site (Friday & Saturday) + virtual experts on demand (Saturday).  
- **Infrastructure**: OpenWebUI hooks ready for your prototype, or bring your own REST/GQL service.  

---

## Technical Preferences
- Integrate directly into **OpenWebUI** (via RAG function) or expose a clean **REST/GQL API**.  
- Prefer **open-source tools** with licenses suitable for federal use.  
- Focus on **explainability, accuracy, and usability**.  

---

## Data
You will have access to the **full corpus of Swiss federal legislation**, provided in multiple formats:

- <a href="https://fedlex.data.admin.ch/sparqlendpoint" class="notion-link link" target="_blank" rel="noopener noreferrer">SPARQL endpoint</a>  
- Directly as HTML assets:  
   • <a href="https://github.com/droid-f/fedlex" class="notion-link link" target="_blank" rel="noopener noreferrer">Metadata</a>  
   • <a href="https://github.com/droid-f/fedlex-assets" class="notion-link link" target="_blank" rel="noopener noreferrer">Assets</a>  
   Maintained as open source generously by **@Gamba** → https://github.com/gamba  

This dataset allows you to build retrieval pipelines, knowledge graphs, or agent-based solutions that stay consistent with the official law text.

---

## Example Task – Input & Expected Output
To help you test your solution, we will release concrete evaluation tasks shortly before the hack.  
Each task will contain a **legal question** and the system should return:

1. **Answer** – concise text, consistent with Swiss federal law.  
2. **Citations** – explicit references (e.g., “Art. 10 BV”, “Art. 5 Abs. 2 OR”).  
3. **Confidence Score** – a numeric or categorical indication of certainty.  

| Ref  | Input Question                                                                 | Expected Output (format)                                                                 |
|------|--------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| Q.a  | “Welche Rechte hat eine Person gemäss Bundesverfassung bei der Meinungsfreiheit?” | **Answer:** Personen haben das Recht, ihre Meinung frei zu bilden, zu äußern und zu verbreiten.<br> **Citations:** Art. 16 BV<br> **Confidence:** 0.93 |
| Q.b  | “Unter welchen Umständen darf ein Arbeitsvertrag in der Probezeit gekündigt werden?” | **Answer:** Während der Probezeit kann ein Arbeitsvertrag mit einer Frist von sieben Tagen gekündigt werden.<br> **Citations:** Art. 335b OR<br> **Confidence:** 0.87 |
| Q.c  | “Welche Datenschutzpflichten bestehen für Bundesbehörden?”                        | **Answer:** Bundesorgane dürfen Personendaten nur rechtmäßig bearbeiten und müssen Transparenz, Zweckbindung und Datensicherheit gewährleisten.<br> **Citations:** Art. 4–7 DSG<br> **Confidence:** 0.91 |


## Why Hack?
- **Real-world impact**: Your prototype can go straight into production inside the Swiss Federal Administration.  
- **Premium dataset**: You’ll work on the **entire corpus of Swiss law**, a unique opportunity to tackle a real-world, high-stakes use case.  

---

## About us
The **Federal Office of Information Technology, Systems and Telecommunication (BIT/FOITT)** is the Swiss government’s in-house tech powerhouse.  
We run over **50 000 workstations**, more than **1 000 specialist applications**, and several state-of-the-art data centres. We also operate a **sovereign GPU stack dedicated to public-sector AI**.  

Your prototype won’t vanish after the hackathon—if it works, it could be deployed directly on infrastructure that already serves the entire Swiss federal administration.  

