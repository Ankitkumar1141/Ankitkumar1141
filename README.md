# Hi, I'm Ankit Kumar Jha 👋

I build, evaluate, and deploy machine learning and LLM systems, from data pipelines and models to containerised services people actually use. 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ankit--kumar--jha-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/ankit-kumar-jha)
[![Email](https://img.shields.io/badge/Email-ankit.aiml625%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:ankit.aiml625@gmail.com)

---

## Open to freelance work

I'm currently open to freelance projects across machine learning and LLM systems: RAG pipelines, LangGraph agents, LLM evaluation and benchmarking, fine-tuning, and deploying ML services. If you have something in mind, get in touch via [LinkedIn](https://linkedin.com/in/ankit-kumar-jha) or [email](mailto:ankit.aiml625@gmail.com).

---

## What I work on

- **RAG systems:** hybrid retrieval, reranking, and evaluation harnesses
- **Agents with LangGraph:** tool-using agents with checkpointing, streaming, and tracing
- **LLM evaluation:** custom metrics, automated scoring, and model benchmarking
- **LLM post-training:** SFT, RLHF, LoRA/PEFT fine-tuning, and data annotation
- **Applied machine learning:** end-to-end pipelines for classification, NLP, and time-series problems
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

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langgraph&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)

| Area | Skills and tools |
|---|---|
| **LLM / GenAI** | Generative AI, LLM post-training, SFT, RLHF, fine-tuning (LoRA/PEFT), data annotation, prompt engineering, GPT-4, LLaMA, Hugging Face Transformers |
| **RAG** | Hybrid dense + BM25 retrieval, Reciprocal Rank Fusion, cross-encoder reranking, chunking strategies, semantic caching |
| **Agents and orchestration** | LangGraph, LangChain, LangSmith (tracing and observability), Model Context Protocol (MCP) |
| **LLM evaluation** | Automated evaluation harnesses, custom metrics (accuracy, coherence, hallucination rate), model benchmarking, multi-stage testing pipelines |
| **Core ML** | PyTorch, TensorFlow, Keras, scikit-learn, XGBoost, LightGBM, Optuna, feature engineering, time-series forecasting, neural networks |
| **Languages** | Python, SQL, Java, C++ |
| **Software engineering** | OOP, LLD, SDLC, REST APIs, Git, Bitbucket, CI/CD |
| **Deployment and MLOps** | Docker, FastAPI, Streamlit, MLflow, AWS (EC2, S3, SageMaker), GCP (Vertex AI) |
| **Databases and vector stores** | MySQL, PostgreSQL, MongoDB, FAISS, ChromaDB, Pinecone, Qdrant |
| **Data analysis** | Pandas, NumPy, Spark, PySpark, Excel, Power BI |

---

## Certifications

- Google Cloud ML Specialization (Vertex AI)
- Deep Learning and NLP Specializations (Coursera)

---

## Let's connect

I'm always happy to talk about machine learning, LLM systems, evaluation, and building things that work in production. Reach me on [LinkedIn](https://linkedin.com/in/ankit-kumar-jha) or at ankit.aiml625@gmail.com.
