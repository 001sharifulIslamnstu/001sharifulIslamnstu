# Bangla RAG TraSe

## TraSe Architecture for Enhanced Retrieval-Augmented Generation in Bangla

This repository contains research materials, implementation structure, and documentation for **TraSe**, a retrieval-augmented generation framework for Bangla, designed for low-resource language understanding and generation.

## Research Problem

Retrieval-Augmented Generation has shown strong performance in English and high-resource languages. However, low-resource languages such as Bangla face several challenges:

- Limited high-quality corpora
- Limited domain-specific datasets
- Weak retrieval quality
- Poor LLM grounding
- Hallucination in generated responses
- Lack of standardized Bangla RAG benchmarks

---

## Research Objective

The objective of this project is to improve Bangla RAG performance by designing a retrieval and generation architecture that can better support low-resource language applications.

```yaml
task:
  - Retrieval-Augmented Generation
  - Bangla Question Answering
  - Low-Resource Language Modeling

language:
  - Bangla

domain:
  - Low-Resource NLP
  - Multilingual NLP
  - Underserved Language Technology
Method Overview
Bangla Documents
      │
      ▼
Text Cleaning and Chunking
      │
      ▼
Embedding Model
      │
      ▼
Vector Database / Retriever
      │
      ▼
Relevant Context Retrieval
      │
      ▼
LLM / Generator
      │
      ▼
Grounded Bangla Response
Expected Repository Structure
bangla-rag-trase/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── corpus_analysis.ipynb
│   ├── retrieval_demo.ipynb
│   └── generation_demo.ipynb
├── src/
│   ├── preprocess.py
│   ├── chunking.py
│   ├── embeddings.py
│   ├── retriever.py
│   ├── generator.py
│   ├── rag_pipeline.py
│   ├── evaluate.py
│   └── utils.py
├── configs/
│   └── default.yaml
├── experiments/
│   └── README.md
├── results/
│   ├── retrieval_scores.csv
│   ├── generation_scores.csv
│   └── examples.md
├── requirements.txt
└── LICENSE
Core Features
Bangla document preprocessing
Text chunking and indexing
Embedding-based retrieval
Retrieval-augmented generation
Bangla response generation
RAG evaluation pipeline
Reproducible experiment structure
Evaluation Metrics
retrieval_metrics:
  - Recall@K
  - Precision@K
  - MRR
  - nDCG

generation_metrics:
  - ROUGE
  - BLEU
  - BERTScore
  - Faithfulness
  - Answer Relevance
  - Context Relevance
Publication

Empowering Low-Resource Languages: TraSe Architecture for Enhanced Retrieval-Augmented Generation in Bangla
Venue: Proceedings of the 1st Workshop on Language Models for Underserved Communities, ACL
Year: 2025
DOI: 10.18653/v1/2025.lm4uc-1.2

Citation
@inproceedings{ipa2025trase,
  title     = {Empowering Low-Resource Languages: TraSe Architecture for Enhanced Retrieval-Augmented Generation in Bangla},
  author    = {Ipa, Atia Shahnaz and Rony, Abu Tareq and Islam, Md. Shariful},
  booktitle = {Proceedings of the 1st Workshop on Language Models for Underserved Communities},
  pages     = {8--15},
  year      = {2025},
  publisher = {Association for Computational Linguistics},
  doi       = {10.18653/v1/2025.lm4uc-1.2}
}
Author

Md Shariful Islam
Google Scholar: https://scholar.google.com/citations?user=-Rut6DAAAAAJ&hl=en

