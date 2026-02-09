# 👋 Hi, I'm Sathwik Matcha

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sathwik-matcha)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matcha.s@northeastern.edu)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mematcha)

Machine Learning Engineer specializing in Large Language Models, Retrieval-Augmented Generation (RAG), and production ML systems. Currently pursuing my Master's in Information Systems at Northeastern University, with hands-on experience building scalable ML solutions and transformer-based architectures.

## 🎓 Education

- **Northeastern University** - M.S. in Information Systems (Dec 2025)
- **Indian Institute of Technology Bombay** - Bachelor of Technology (Apr 2021)

## 💼 Professional Experience

- **AI Engineer Intern** @ Gaman AI (Jan 2025 - Present)
  - Leading development of production LLM systems with Graph RAG architecture
  - Reduced inference latency by 53% through optimization and caching strategies
  - Built scalable ML pipelines on AWS with Docker and Kubernetes

- **Software Engineer** @ 5Paisa Capital Limited (June 2021 - July 2023)
  - Developed real-time trading platform serving 50,000+ monthly users
  - Built ML-driven recommendation systems improving engagement by 28%
  - Designed and executed A/B tests for data-driven product decisions

## 💻 Technical Skills

### Machine Learning & AI
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=for-the-badge)
![LangChain](https://img.shields.io/badge/🦜_LangChain-121212?style=for-the-badge)

**Specializations:** Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), Transformers, BERT, LayoutLMv3, Neural Networks, NLP, Recommendation Systems, Multi-Armed Bandits, A/B Testing

### Development & Infrastructure
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

### MLOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Data & Frameworks
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

## 🚀 Featured Projects

### [Dynamic Multi-Model GPU Serving Platform (GKE, FastAPI)](https://github.com/mematcha/dynamic-model-serving/)
- **Delivered a production-grade GPU inference system with stable p95 latency**, by architecting a Kubernetes-based FastAPI service on NVIDIA L4 GPUs, resulting in cost-efficient multi-model serving.
- **Reduced cold-start variance and stabilized latency**, by designing a decoupled model-loader with FP16 weights, GPU caching, and dynamic request routing, ensuring predictable inference performance.
- **Quantified a 4.3× latency and throughput gap between SDXL and SD 1.5**, by building a benchmarking harness capturing per-request latency distributions and warmup behavior, enabling data-driven capacity planning.
- **Enabled secure downstream consumption of ML inference**, by exposing authenticated REST APIs, resulting in safe integration with client applications.

### [Automated Batch Feature Store](https://github.com/mematcha/automated-feature-store)
- Engineered feature pipeline achieving **170K+ records/sec** with fault-tolerant checkpointing, cutting feature engineering effort by **60–80%**.
- Achieved **0.04 ms average latency** at **27K ops/sec** for real-time feature serving via Redis, enabling model inference for production systems at scale.

### [Meridian — Multi-Agent Financial Intelligence Platform](https://github.com/Big-Data-Team-3/project-meridian)
*Dec 2025*

- **Orchestrated an autonomous multi-agent analysis system processing 10,000+ articles/day**, by designing an eight-agent LLM workflow ingesting data from 4+ market and news sources, resulting in explainable BUY/HOLD/SELL recommendations.
- **Achieved sub-4-minute end-to-end decision latency**, by optimizing long-horizon agent execution and tool invocation (<1 minute per agent), enabling near–real-time financial insights.
- **Sustained 100+ queries/hour under a <$2 per-query token budget**, by deploying Dockerized services on GCP with CI/CD, resulting in a cost-efficient and scalable agentic system.



### 🔍 [Large-Scale Document Understanding with Multi-Modal Transformers](https://github.com/Big-Data-Team-3/pdf-parser)
Built production-scale ML pipeline for SEC financial document processing using **LayoutLMv3** and **LayoutParser**
- Multi-engine architecture combining deep learning models (Google Document AI, Docling) with traditional parsers
- Automated quality assessment pipeline with confidence scoring achieving 92% extraction accuracy
- Orchestrated using DVC with structured outputs (JSON, CSV, Markdown) for reproducible ML experiments
- **Tech:** PyTorch, Transformers, LayoutLMv3, Google Document AI, DVC, Docker

### 📚 [Large-Scale Legal Document RAG with LLM Evaluation](https://github.com/mematcha/arizona-caselaw-rag)
Production-ready Retrieval-Augmented Generation system for legal document analysis
- Processed 2GB+ of Arizona case law data across 100,000+ documents using FAISS vector search
- Built comprehensive LLM evaluation pipeline with BLEU, ROUGE, and reward modeling metrics
- Deployed via Streamlit for public access with semantic retrieval capabilities
- **Tech:** LangChain, FAISS, OpenAI API, Streamlit, RAG, Vector Search

### 🖼️ Image Caption Generation with MSCOCO Dataset
Neural encoder-decoder model with attention mechanisms for image captioning
- Combined Inception V3 feature extraction with LSTM/GRU architectures
- Achieved BLEU-4 scores of 0.28+ and METEOR scores of 0.25+ on MSCOCO dataset
- Optimized inference time by 35% through mixed-precision training and model quantization
- **Tech:** TensorFlow, CNNs, RNNs, Attention Mechanisms

### ⚡ Efficient Parallelization for NLP Model Training
Distributed data processing system for large-scale NLP
- Architected scalable pipeline using Python multiprocessing and Dask for 2M+ records
- Demonstrated expertise in designing efficient solutions for large-scale text processing
- **Tech:** Python, Dask, Multiprocessing, NLP, Distributed Computing

---

⭐️ From [mematcha](https://github.com/mematcha)
