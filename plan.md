# 🧠 Data Analyst to Full-Stack Data Scientist: LLM-Focused 10-Week Plan

## Overview
A 10-week self-study plan for data analysts with a CS background aiming to transition into data science roles with an emphasis on data engineering and LLM (Large Language Model) integration.

---

## Week 0: Setup & Environment
- **Read**:
  - [Full Stack Deep Learning Overview](https://fullstackdeeplearning.com/)
  - [Hidden Technical Debt in ML Systems (paper)](https://papers.nips.cc/paper_files/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf)
- **Setup**:
  - Python (poetry or pipenv), VSCode, Jupyter Lab
  - Accounts: Hugging Face, Kaggle, Colab, Weights & Biases
- **Repos**:
  - https://github.com/fastai/fastbook
  - https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2021
- **Bonus**: Define a capstone idea involving LLM + data pipeline

---

## Week 1: Transformers Core
- **Read**:
  - [Attention Is All You Need](https://arxiv.org/pdf/1706.03762)
  - [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
- **Build**:
  - Transformer from scratch (or use [lucidrains/x-transformers](https://github.com/lucidrains/x-transformers))
  - Tokenize + visualize attention
- **Repo**: https://github.com/karpathy/minGPT
- **Bonus**: Build simple SQL-to-English LLM

---

## Week 2: Embeddings + Retrieval (RAG)
- **Read**:
  - *BERT*, *Chinchilla Scaling Laws*
- **Build**:
  - Embed docs with BERT → FAISS/Chroma vector store
  - Basic RAG pipeline (ask PDF)
- **Repos**:
  - https://github.com/langchain-ai/langchain
  - https://github.com/deepset-ai/haystack

---

## Week 3: Fine-Tuning + LoRA
- **Read**:
  - *LoRA*, *InstructGPT*
- **Build**:
  - Fine-tune small model using Hugging Face + PEFT
- **Repo**:
  - https://github.com/oobabooga/text-generation-webui
- **Bonus**: Fine-tune personal assistant on Slack/Teams data

---

## Week 4: LangChain Agents + Toolformer
- **Read**:
  - *Toolformer*, LangChain docs
- **Build**:
  - RAG + tool integrations (web, calculator, code exec)
- **Repos**:
  - https://github.com/langchain-hub

---

## Week 5: Data Engineering with LLMs
- **Read**:
  - Databricks blog on LLM ETL
  - Clean architecture blogs
- **Build**:
  - ETL: Prefect or Airflow → LLM tagger/summarizer → DB
- **Repos**:
  - https://github.com/PrefectHQ/marvin
  - https://github.com/deepset-ai/haystack

---

## Week 6: Feature Engineering + Classic ML
- **Read**:
  - Feature Engineering (Alteryx), Pandas design patterns
- **Build**:
  - SQL to feature matrix → XGBoost model → SHAP plots
- **Repo**:
  - https://github.com/alteryx/featuretools

---

## Week 7: ML APIs + Deployment
- **Read**:
  - Chip Huyen ML Systems Design
  - LLMOps intro
- **Build**:
  - FastAPI + Docker + Deploy on GCP/AWS
- **Repos**:
  - https://github.com/bentoml/BentoML
  - https://github.com/modal-labs/modal-client

---

## Week 8: Interpretability + Safety
- **Read**:
  - Claude papers, *Sparks of AGI*
- **Build**:
  - Logit lens/token exploration, jailbreak detection
- **Repo**:
  - https://github.com/openai/openai-cookbook

---

## Weeks 9–10: Capstone Build
### Option 1: Full-Stack LLM Agent
- Resume/chatbot over your docs
- Tools, embeddings, prompt tracking
- Streamlit or Gradio UI

### Option 2: ETL + LLM Ops
- Prefect or Airflow
- Cloud trigger + deployment
- Vectorstore + logging dashboard

---

## Bonus Resources
### TeachYourselfCS-Style
- https://fullstackdeeplearning.com/
- https://huyenchip.com/ml-interviews-book/
- https://course.fast.ai/

### YouTube & GitHub
- https://jalammar.github.io/
- https://www.youtube.com/c/YannicKilcher
- https://huggingface.co/learn/nlp-course

### Competitions
- https://www.kaggle.com/competitions
- https://huggingface.co/datasets
