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


---

# 3. `low-resource-nlp/bangla-llm-summarization/README.md`

```markdown
# Bangla LLM Summarization

## Evaluating Large Language Models for Summarizing Bangla Texts

This repository contains the research structure for evaluating large language models on Bangla text summarization.

## Research Problem

Large Language Models have achieved strong performance in English summarization. However, their performance on Bangla remains less explored due to:

- Limited Bangla summarization benchmarks
- Tokenization challenges
- Morphological richness
- Domain mismatch
- Lack of robust human and automatic evaluation
- Hallucination in generated summaries

---

## Research Objective

The goal of this project is to evaluate LLMs for Bangla text summarization and analyze their strengths, weaknesses, and failure cases.

```yaml
task:
  - Bangla Text Summarization
  - LLM Evaluation
  - Low-Resource NLP

language:
  - Bangla

model_family:
  - Large Language Models
  - Transformer Models
  - Sequence-to-Sequence Models
Method Overview
Bangla Input Text
      │
      ▼
Preprocessing and Tokenization
      │
      ▼
LLM / Summarization Model
      │
      ▼
Generated Summary
      │
      ▼
Automatic Evaluation + Human Error Analysis
Expected Repository Structure
bangla-llm-summarization/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── dataset_analysis.ipynb
│   ├── model_comparison.ipynb
│   └── error_analysis.ipynb
├── src/
│   ├── preprocess.py
│   ├── dataset.py
│   ├── summarize.py
│   ├── evaluate.py
│   ├── metrics.py
│   └── utils.py
├── configs/
│   └── default.yaml
├── experiments/
│   └── README.md
├── results/
│   ├── generated_summaries/
│   ├── evaluation_scores.csv
│   └── qualitative_analysis.md
├── requirements.txt
└── LICENSE
Core Features
Bangla text preprocessing
LLM-based summarization pipeline
Summarization evaluation
Model comparison
Error analysis
Hallucination and factuality inspection
Reproducible experiment setup
Evaluation Metrics
automatic_metrics:
  - ROUGE-1
  - ROUGE-2
  - ROUGE-L
  - BLEU
  - BERTScore

qualitative_analysis:
  - Factual Consistency
  - Fluency
  - Coverage
  - Conciseness
  - Hallucination
  - Missing Key Information
Publication

Evaluating Large Language Models for Summarizing Bangla Texts
Venue: Eighth Widening NLP Workshop, WiNLP 2024, Phase II
Year: 2024

Citation
@inproceedings{rony2024banglallmsummarization,
  title     = {Evaluating Large Language Models for Summarizing Bangla Texts},
  author    = {Rony, Md. Abu Tareq and Islam, Md. Shariful},
  booktitle = {Eighth Widening NLP Workshop},
  year      = {2024},
  note      = {WiNLP 2024 Phase II}
}
