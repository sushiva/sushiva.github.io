![Banner](banner.png)

# 👋 Hi, I'm **Sudhir Shivaram**  
**ML/AI Engineer | Full‑Stack Java Engineer | Cloud & MLOps Practitioner**

---

## 🧑‍💻 About Me
ML/AI Engineer with **12+ years in full‑stack Java engineering** and proven expertise in **production‑grade RAG systems, ML pipelines, and cloud‑deployed AI solutions**. Skilled in **Python, LLMs, vector databases, and AWS/Azure/GCP**, combining software engineering rigor with modern AI techniques.

---

## 🧠 Skills

### 🔹 AI/ML & Data Science
- **Programming:** Python, PyTorch, TensorFlow, scikit‑learn, LangChain, LlamaIndex  
- **ML Techniques:** RAG, NLP, Supervised/Unsupervised Learning, LLMs, Prompt Engineering, LoRA Fine‑tuning  
- **Vector Databases & Search:** FAISS, Pinecone, Weaviate, ChromaDB, OpenSearch  
- **Data Engineering:** Pandas, NumPy, SQL, ETL (Airflow, dbt, AWS Glue), Feature Engineering  
- **Deployment & MLOps:** Docker, FastAPI, Streamlit, MLflow, HuggingFace Spaces  
- **Cloud Platforms:** AWS (Glue, S3, Lambda), Azure, GCP  

### 🔹 Software Engineering
- **Languages:** Java (JDK 17), Python  
- **Backend:** Spring Boot, REST APIs, FastAPI, Flask, Jersey  
- **Frontend:** React JS, Angular (legacy experience)  
- **Databases:** Oracle, MySQL, PostgreSQL, Snowflake, BigQuery, Redshift  
- **DevOps:** Jenkins, GitHub Actions, Azure DevOps, Docker, OpenShift, Kubernetes  
- **Monitoring & Security:** Splunk, Dynatrace, Veracode  
- **Collaboration:** Jira, Confluence, Git, Agile/Scrum  

---

## 🏅 Certifications
- Microsoft Certified: Azure Fundamentals (AZ‑900)  
- AWS Certified Cloud Practitioner (CLF‑002)  
- Post Graduate Certificate in AI/ML – UT Austin, McCombs School of Business  

---

# 🚀 Professional Projects

## 📌 Computershare — Senior Software Engineer  
**June 2025 – Present**  
**Tech Stack:** Java (JDK 17), Spring, Power BI, REST API, Azure, OpenShift, Docker, SQL  

- Engineered a workaround for Power BI REST API limitations by converting Excel responses to CSV via HTTPEntity  
- Optimized report generation for 1,000+ account IDs, reducing latency and improving scalability  
- Shifted sensitive data processing to server‑side, strengthening application security  
- Migrated legacy Java apps to **Azure Cloud** with OpenShift containers  
- Led L3 production triage, coordinating cross‑functional teams to resolve incidents within SLA  
- Partnered with business stakeholders for transparent issue remediation and improved trust  

---


## 📌 Predictive Research Inc. — Research Associate  
**May 2023 – June 2025**
## **Project: PowerGrid AI Tutor — Advanced RAG System for Electrical Engineering & Renewable Energy**

**Live Demo:**  
🔗 **HuggingFace Space:** [https://huggingface.co/spaces/sudhirshivaram/powergrid-ai-tutor](https://huggingface.co/spaces/sudhirshivaram/powergrid-ai-tutor)  
🔗 **GitHub Repository:** [https://github.com/sushiva/powergrid-ai-tutor](https://github.com/sushiva/powergrid-ai-tutor)

**Tech Stack:** Python, LlamaIndex, FAISS, Gradio, Google Gemini, OpenAI GPT-4, Cohere Rerank, BM25, arXiv API

---

![PowerGrid AI Tutor Demo](./screenshots/powergrid-demo.png)
_Screenshot: Interactive AI tutor with query expansion, hybrid search, and reranking_

---
#### **Key Achievements:**

- **Production Deployment:** Built and deployed full-featured RAG system on HuggingFace Spaces with dual LLM support (Gemini + OpenAI)
- **Advanced Retrieval Pipeline:** Implemented hybrid search combining BM25 keyword matching + FAISS vector search with Cohere reranking
- **Intelligent Query Processing:** Engineered query expansion system generating 3-5 alternative queries, improving retrieval coverage by 35%+
- **Domain-Specific Knowledge Base:** Curated and indexed 50+ research papers on electrical engineering, renewable energy, and smart grids from arXiv
- **Smart Routing:** Built domain classifier to gracefully handle out-of-scope questions with friendly, conversational rejection messages

#### **Technical Implementation:**

- **Frontend:** Gradio UI with emoji-enhanced interface, real-time status updates, collapsible documentation, and example questions
- **Retrieval Architecture:** 3-stage pipeline: Query Expansion → Hybrid Search (BM25 + Vector) → Cohere Rerank-3 for optimal relevance
- **Vector Store:** FAISS index with 1536-dimensional embeddings, supporting metadata filtering by topic and document type
- **LLM Integration:** Multi-provider support (Google Gemini 2.0 Flash, OpenAI GPT-4o-mini) with intelligent prompt engineering
- **Data Collection:** Automated arXiv scraping pipeline for solar, wind, battery, and smart grid research papers with metadata extraction
- **Evaluation Framework:** Comprehensive RAG evaluation with RAGAS metrics tracking faithfulness, relevance, and context precision

#### **Impact & Metrics:**

- **Documents Indexed:** 50+ research papers across 4 domains (Solar, Wind, Battery Storage, Smart Grids)
- **Query Performance:** Sub-3 second response time with full hybrid search + reranking pipeline
- **Retrieval Accuracy:** 40% improvement in relevance scores with reranking vs vector search alone
- **Advanced Features:** 3 toggleable retrieval enhancements (Query Expansion, Hybrid Search, Reranking)
- **User Experience:** Friendly conversational responses, source citations with relevance scores, topic-based filtering

#### **Advanced RAG Features:**

- **Query Expansion:** LLM-powered generation of semantically similar queries for comprehensive retrieval
- **Hybrid Search:** Combined BM25 (keyword) + FAISS (semantic) with Reciprocal Rank Fusion (RRF)
- **Reranking:** Cohere Rerank-3 model for final relevance optimization
- **Metadata Filtering:** Filter by topic (Solar/Wind/Battery/Grid) and source type (Papers/Standards)
- **Source Attribution:** Top-3 most relevant sources with similarity scores for transparency

---

**🔗 Links:**
- **Try it live:** [HuggingFace Demo](https://huggingface.co/spaces/sudhirshivaram/powergrid-ai-tutor)
- **Source Code:** [GitHub Repository](https://github.com/sushiva/powergrid-ai-tutor)
- **Documentation:** [Architecture & Implementation Details](https://github.com/sushiva/powergrid-ai-tutor/tree/main/docs)

---

### **Project: arXiv Paper Curator + Financial Documents RAG — Production AI Research Assistant**

**Live Demo:**  
🔗 **Frontend:** [https://your-app.streamlit.app](https://your-app.streamlit.app) _(Deploy tomorrow)_  
🔗 **Backend API:** [https://arxiv-paper-curator-v1-production.up.railway.app/docs](https://arxiv-paper-curator-v1-production.up.railway.app/docs)  

**Tech Stack:** Python, FastAPI, Railway, OpenSearch, PostgreSQL, Streamlit, Google Gemini, Anthropic Claude, OpenAI, Jina AI Embeddings

---

![RAG System Demo](./screenshots/rag-demo.png)
_Screenshot: Dual RAG system querying arXiv papers and SEC financial filings_

---

#### **Key Achievements:**

- **Production Deployment:** Deployed full-stack RAG system on Railway with 99%+ uptime via 4-tier LLM fallback (Gemini → Claude → OpenAI)
- **Dual-Index Architecture:** Built separate search indices for 200+ arXiv papers and SEC 10-K/10-Q filings with hybrid search (BM25 + vector embeddings)
- **Cost Optimization:** Engineered 4-tier automatic LLM fallback reducing monthly costs to ~$12 while maintaining reliability (Gemini free tier → paid backups)
- **High Accuracy:** Achieved 95%+ document retrieval relevance through Reciprocal Rank Fusion (RRF) pipeline
- **Financial Document Processing:** Implemented SEC EDGAR API integration with automated metadata extraction for 7 major tech companies

#### **Technical Implementation:**

- **Backend:** FastAPI + PostgreSQL (metadata) + OpenSearch (vector search) deployed on Railway
- **Search Pipeline:** Hybrid search combining BM25 keyword matching with Jina embeddings (1024-dim vectors)
- **LLM Integration:** Multi-provider support (Google Gemini 2.0, Claude 3.5 Haiku, OpenAI GPT-4o-mini) with automatic tier fallback
- **Data Ingestion:** Chunked 200+ documents with overlap strategy, extracted named entities, enriched metadata
- **Frontend:** Streamlit UI with document type selector, ticker filtering, and streaming responses

#### **Impact & Metrics:**

- **Documents Indexed:** 200+ (100 arXiv papers + 100 SEC filings)
- **Query Performance:** ~2-3 second response time with hybrid search
- **Relevance Improvement:** 40% better results vs BM25-only through vector similarity
- **Production Reliability:** 4-tier fallback ensures 99.9%+ uptime for recruiter demos
- **Monthly Cost:** ~$12 (optimized for free tier LLM usage)

---

**🔗 Links:**
- **Try it live:** [Streamlit Demo](https://your-app.streamlit.app) _(coming tomorrow)_
- **API Docs:** [FastAPI Swagger](https://arxiv-paper-curator-v1-production.up.railway.app/docs)
- **Source Code:** [GitHub Repository](https://github.com/sudhirshivaram/arxiv-paper-curator-v1)

---

### **Project: Energy Consumption Forecasting System**  
**Tech Stack:** Python, XGBoost, SHAP, scikit‑learn, Streamlit, Docker, HuggingFace Spaces  

- Achieved **99.82% R²** and **0.42% MAPE** using XGBoost on 19,735 records  
- Engineered 15+ time‑series features, boosting accuracy by **35%**  
- Applied SHAP for interpretability, revealing key consumption drivers  
- Deployed full ML pipeline with evaluation metrics (RMSE, MAE, MAPE)  
- Built real‑time prediction dashboard on HuggingFace Spaces  

---

# 🎓 Academic Projects
- 📘 *LLM‑Powered Document QA Assistant* — Built with LangChain + FAISS, enabling domain‑specific Q&A over PDFs  
- 📊 *Retail Demand Forecasting* — Implemented XGBoost with feature engineering, achieving 92% accuracy on Kaggle dataset  
- 🤖 *Neural Network Classifier for Image Data* — Developed CNN model for image recognition with TensorFlow  

---

# 🤝 Connect With Me
- **GitHub:** [SudhirShivaram](https://github.com/SudhirShivaram)  
- **LinkedIn:** [linkedin.com/in/sudhirshivaram](https://linkedin.com/in/sudhirshivaram)  
- **Email:** sudhir.shivaram@email.com  
