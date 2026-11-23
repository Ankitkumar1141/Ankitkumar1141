# Hi, I'm Ankit Kumar Jha 👋

I build, evaluate, and deploy machine learning and LLM systems, from data pipelines and models to containerised services people actually use. Based in New Delhi, India.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ankit--kumar--jha-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ankit-kumar-jha)
[![Email](https://img.shields.io/badge/Email-ankit.aiml625%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:ankit.aiml625@gmail.com)

---

## What I work on

- **Retrieval and LLM systems:** hybrid retrieval, reranking, and evaluation harnesses
- **Agents and tooling:** tool-using agents with checkpointing, streaming, and tracing
- **Applied machine learning:** end-to-end pipelines for classification, NLP, and time-series problems
- **Evaluation and benchmarking:** custom metrics, automated scoring, and model comparison
- **Deployment:** Docker, FastAPI, and cloud services on AWS and GCP

---

## Featured projects

### [NexusRAG](https://github.com/Ankitkumar1141/NexusRAG)
A hybrid RAG engine combining parent-child hierarchical chunking, concurrent dense (FAISS) and sparse (BM25) retrieval, and Reciprocal Rank Fusion, followed by two-stage cross-encoder reranking and a SHA-256 LRU semantic cache.
- 98.6% Recall@K, 0.996 MRR, and 100% faithfulness on an automated 110-case benchmark
- ~1.01s query latency, sub-50ms on cached hits
- `Python` `LangChain` `FAISS` `Pinecone` `BM25` `Mistral` `Gemini` `Streamlit` `Docker`

### [Cortex](https://github.com/Ankitkumar1141/Cortex)
A LangGraph conversational agent with a Pydantic-validated intent router that sends each turn to either direct chat or a 12-tool agentic loop (web search, weather, finance, arXiv, URL scraping, and more).
- Per-thread SQLite checkpointing, response streaming with a live tool-status UI, and LangSmith tracing
- `Python` `LangGraph` `LangChain` `MCP` `FastAPI` `Streamlit` `Mistral AI`

### [Churn Modelling](https://github.com/Ankitkumar1141/Churn-modelling)
An end-to-end churn prediction pipeline on 10,000 relational customer records, benchmarking 8 algorithms with Optuna tuning.
- 0.84 ROC-AUC, with minority-class recall raised to 75.7% after handling 36% missing balances and a 4:1 class imbalance
- Experiments tracked in MLflow, predictions served via FastAPI in Docker
- `Python` `XGBoost` `LightGBM` `scikit-learn` `Optuna` `MLflow` `FastAPI` `Docker`

---

## Experience highlights

- **Ethara AI** (Feb 2026 – Sep 2026): automated large-scale LLM output evaluation (50% less manual assessment time across 1,000+ prompt variations), designed evaluation frameworks that cut new-model onboarding from 5 days to 2, and benchmarked 5+ LLMs to inform model selection.
- **Freelance** (Nov 2024 – Jun 2026): delivered 3+ end-to-end ML pipelines and deployed containerised services on AWS EC2 and GCP for 45+ daily active users, including a churn model with a 12-point accuracy lift over baseline.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)

| Area | Tools |
|---|---|
| **LLM / GenAI** | RAG, LangChain, LangGraph, LangSmith, Hugging Face Transformers, LoRA/PEFT, prompt engineering, MCP |
| **Machine learning** | PyTorch, TensorFlow, Keras, scikit-learn, XGBoost, LightGBM, Optuna, time-series forecasting |
| **Data and storage** | Pandas, NumPy, Spark/PySpark, MySQL, PostgreSQL, MongoDB, FAISS, ChromaDB, Pinecone, Qdrant |
| **Deployment** | Docker, FastAPI, Streamlit, MLflow, AWS (EC2, S3, SageMaker), GCP (Vertex AI), CI/CD |
| **Analysis** | Excel, Power BI |

---

## Certifications

- Google Cloud ML Specialization (Vertex AI)
- Deep Learning and NLP Specializations (Coursera)

---

## Let's connect

I'm always happy to talk about machine learning, LLM systems, evaluation, and building things that work in production. Reach me on [LinkedIn](https://linkedin.com/in/ankit-kumar-jha) or at ankit.aiml625@gmail.com.
