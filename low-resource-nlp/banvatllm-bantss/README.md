# BanVATLLM and BanTSS

## Multimodal Framework and Dataset for Detecting Toxic Speech in Bangla and Bangla-English Videos

This repository contains the research structure for **BanVATLLM and BanTSS**, a multimodal framework and dataset for detecting toxic speech in Bangla and Bangla-English video content.

## Research Problem

Toxic speech detection in Bangla and Bangla-English videos is challenging because harmful meaning may appear across multiple modalities:

- Spoken content
- Transcribed text
- Visual context
- Code-mixed language
- Tone and expression
- Video-level context

Most toxic speech detection systems focus mainly on text, which may miss important multimodal signals.

---

## Research Objective

The objective of this project is to develop a multimodal toxic speech detection framework and dataset for Bangla and Bangla-English videos.

```yaml
task:
  - Toxic Speech Detection
  - Multimodal Classification
  - Bangla-English Code-Mixed NLP

language:
  - Bangla
  - Bangla-English

modality:
  - Video
  - Audio
  - Text
Method Overview
Bangla / Bangla-English Video
      │
      ├──► Audio Extraction
      ├──► Speech-to-Text / Transcript Processing
      ├──► Visual Feature Extraction
      └──► Metadata / Context Processing
                    │
                    ▼
             Multimodal Fusion
                    │
                    ▼
          Toxic Speech Classifier
Expected Repository Structure
banvatllm-bantss/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── dataset_statistics.ipynb
│   ├── annotation_analysis.ipynb
│   └── model_demo.ipynb
├── src/
│   ├── preprocess_audio.py
│   ├── preprocess_text.py
│   ├── preprocess_video.py
│   ├── dataset.py
│   ├── fusion.py
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
│   └── examples.md
├── requirements.txt
└── LICENSE
Core Features
Bangla and Bangla-English toxic speech detection
Multimodal video understanding
Dataset organization and documentation
Text, audio, and visual feature extraction
Multimodal fusion
Reproducible training and evaluation pipeline
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
  - Class-wise Error Analysis
  - Modality Ablation
  - Cross-Domain Evaluation
Publication

BanVATLLM and BanTSS: A Multimodal Framework and a Dataset for Detecting Toxic Speech in Bangla and Bangla-English Videos
Venue: WiNLP 2024, Phase II
Year: 2024

Citation
@inproceedings{islam2024banvatllm,
  title     = {BanVATLLM and BanTSS: A Multimodal Framework and a Dataset for Detecting Toxic Speech in Bangla and Bangla-English Videos},
  author    = {Islam, Md. Shariful and Rony, Md. Abu Tareq},
  booktitle = {Widening NLP Workshop},
  year      = {2024},
  note      = {WiNLP 2024 Phase II}
}
Author

Md Shariful Islam
Google Scholar: https://scholar.google.com/citations?user=-Rut6DAAAAAJ&hl=en
