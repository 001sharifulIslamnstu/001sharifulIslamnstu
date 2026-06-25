
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
