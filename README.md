# Mudit Tandon

Master's Student in Applied Computer Science — University of Göttingen, Germany  
Hands-on experience building LLM-powered applications and RAG pipelines. Seeking Werkstudent or internship roles in Software Engineering or Generative AI.

📧 [mudittandon34@gmail.com](mailto:mudittandon34@gmail.com) · [LinkedIn](https://www.linkedin.com/in/mudit-tandon-b05481204/) · 📍 Göttingen, Germany

---

## Education

**M.Sc. Applied Computer Science** — University of Göttingen *(Expected 2027)*  
Relevant Coursework: Cloud Computing, Parallel Computing, Data Management for Data Science, AI in Networking, Android Development, Requirements Engineering

**B.Tech Information Technology** — Guru Tegh Bahadur Institute of Technology, New Delhi *(2020 – 2024)*  
CGPA: 9.47/10 (Top 5% of cohort)

---

## Experience

**Student Assistant (Studentische Hilfskraft) — AI-Exam FORGE** *(Jan 2026 – Apr 2026)*  
University of Göttingen, Department für Agrarökonomie und Rurale Entwicklung

- Built a Flask REST API with a `/generate` endpoint that accepts an Arcana document ID and question type, orchestrating a two-stage LLM pipeline to return structured exam content.
- Implemented a two-step generation pipeline: (1) auto-detect document topic and extract 15 keywords via LLM, (2) randomly sample 3 keywords and generate questions across two randomized focus areas (*Grundlagen / Analyse*).
- Developed question generation logic for MCQ sets (10 items with labeled answers) and open-ended questions with detailed model answers, using `meta-llama-3.1-8b-instruct` via the GWDG Academic Cloud API.
- Built a German-language web frontend with async fetch, real-time loading states, and error handling for instructor use.

---

## Projects

**AI-Exam FORGE** — *Python, Flask, LLaMA 3.1, OpenAI-compatible API, RAG, HTML/CSS/JS*

- Developed a Flask web app integrating an OpenAI-compatible LLM API (GWDG Academic Cloud) with Arcana RAG to generate exam questions directly from indexed academic documents.
- Designed a dynamic context pipeline: LLM scans the document to extract 15 keywords, randomly samples 3 per run, and selects focus prompts from predefined pools — producing varied, non-repetitive output across generations.
- Implemented output post-processing to strip source citations, metadata headers, and cut-off markers from raw LLM responses before returning clean content to the client.
- Supported two question formats: structured MCQ (10 questions, A–D options, labeled answer) and open-ended theory (2 questions with full *Musterlösung*), selectable via frontend dropdown.
- Tuned LLM generation parameters (temperature 0.8, top_p 0.95) for output diversity; added deliberate inter-batch delays to handle API rate limits reliably.

**[SWASTHYA-SERVICES](https://swasthya-serivce.onrender.com/)** — *React.js, Node.js, Express.js, MongoDB, REST APIs*

- Built a full-stack healthcare platform providing access to real-time medical services, developed as a 4-person Bachelor's capstone project.
- Designed and implemented RESTful APIs using Node.js and Express.js covering user authentication, service management, and request handling.
- Built a responsive React.js frontend with component-based architecture, integrating seamlessly with backend APIs.
- Used MongoDB with Mongoose for data modelling and efficient retrieval across multiple service categories.

---

## Skills

**Programming Languages:** Python, JavaScript, TypeScript, C++  
**Frameworks & Libraries:** React.js, Node.js, Express.js, Flask, LangChain  
**Databases:** MongoDB  
**AI / GenAI:** Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Prompt Engineering, LLM API Integration  
**Tools & Platforms:** Git, GitHub, Postman, REST APIs, GWDG Academic Cloud, Render, Netlify

---

## Languages

**Hindi, Punjabi:** Native  
**English:** C2  
**German:** A2
