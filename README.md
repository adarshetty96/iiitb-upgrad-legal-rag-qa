# IIITB-UpGrad Legal RAG QA System

This project implements a Retrieval-Augmented Generation (RAG) pipeline for answering questions over legal documents using LangChain and GROQ API.

## 📚 Project Overview
- Processes legal contracts across four domains: `contractnli`, `cuad`, `maud`, and `privacy_qa`.
- Chunks and embeds large documents using Sentence-Transformers.
- Retrieves relevant chunks via FAISS and generates answers using a GPT-based LLM.
- Evaluated on benchmark Q&A sets using ROUGE, BLEU, and semantic similarity.


## 🛠️ Setup

```bash
pip install -r requirements.txt
```

jupyter notebook notebooks/RAG_Legal_QA_Final.ipynb


📊 Evaluation Metrics (100 Q&A)
ROUGE-1: 0.274

ROUGE-L: 0.181

BLEU: 0.027

Semantic Similarity: 0.631



