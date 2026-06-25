# Bangla Sentiment LLM

## LLM-Based Sentiment Analysis for Bangla and Product Review Understanding

This repository is designed for Bangla sentiment analysis using large language models, transformer-based models, and reproducible NLP evaluation pipelines.

## Research Problem

Sentiment analysis in Bangla and code-mixed contexts is challenging due to:

- Limited annotated datasets
- Informal spelling variation
- Code-mixing
- Domain-specific product language
- Sarcasm and implicit sentiment
- Lack of robust benchmark comparisons

---

## Research Objective

The goal of this project is to develop and evaluate LLM-based methods for sentiment analysis in Bangla and related low-resource language settings.

```yaml
task:
  - Sentiment Analysis
  - Product Review Classification
  - Low-Resource NLP
  - LLM Evaluation

language:
  - Bangla
  - Bangla-English

label_space:
  - Positive
  - Negative
  - Neutral
Method Overview
Bangla / Product Review Text
      │
      ▼
Text Cleaning and Normalization
      │
      ▼
Tokenizer / Embedding Model
      │
      ▼
LLM or Transformer Encoder
      │
      ▼
Sentiment Classification Head
      │
      ▼
Positive / Negative / Neutral Prediction
Expected Repository Structure
bangla-sentiment-llm/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── dataset_analysis.ipynb
│   ├── baseline_models.ipynb
│   └── error_analysis.ipynb
├── src/
│   ├── preprocess.py
│   ├── dataset.py
│   ├── prompts.py
│   ├── model.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
├── configs/
│   └── default.yaml
├── experiments/
│   └── README.md
├── results/
│   ├── classification_report.csv
│   ├── confusion_matrix.png
│   └── qualitative_errors.md
├── requirements.txt
└── LICENSE
Core Features
Bangla text cleaning and normalization
Product review sentiment analysis
LLM prompt-based classification
Transformer fine-tuning pipeline
Baseline ML model comparison
Error analysis and misclassification review
Reproducible evaluation setup
Baseline Models
traditional_ml:
  - Logistic Regression
  - Support Vector Machine
  - Random Forest
  - XGBoost

deep_learning:
  - BiLSTM
  - CNN
  - Transformer Encoder

llm_methods:
  - Zero-shot Prompting
  - Few-shot Prompting
  - Instruction-Tuned LLM Evaluation
  - Fine-Tuning
Evaluation Metrics
classification_metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Macro-F1
  - Weighted-F1

analysis:
  - Confusion Matrix
  - Error Analysis
  - Domain Generalization
  - Prompt Sensitivity
  - Class Imbalance Analysis
Publication

Add final publication information here after confirmation.

paper_title: Add final title
venue: Add journal or conference
year: Add year
doi: Add DOI
pdf: Add PDF link
code: Add code link
Citation
@misc{islam_bangla_sentiment_llm,
  title  = {Bangla Sentiment LLM: LLM-Based Sentiment Analysis for Bangla and Product Review Understanding},
  author = {Islam, Md. Shariful},
  year   = {2025},
  note   = {Add final publication venue and DOI after confirmation}
}
Author

Md Shariful Islam
Google Scholar: https://scholar.google.com/citations?user=-Rut6DAAAAAJ&hl=en
