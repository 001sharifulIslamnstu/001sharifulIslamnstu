# SarcasmSense

## Multitask Learning for Political Sarcasm and Irony Detection in Vlogs

This repository is for **SarcasmSense**, a multimodal research project focused on detecting sarcasm and irony in political vlog-based content.

## Research Problem

Sarcasm and irony detection is difficult because the meaning of an utterance often depends on more than text alone.

In political vlogs, sarcasm may be expressed through:

- Spoken language
- Facial expressions
- Voice tone
- Visual context
- Political topic framing
- Contrast between literal and intended meaning

---

## Research Objective

The goal of this project is to develop a **multitask learning framework** for identifying political sarcasm and irony using multimodal video data.

```yaml
task:
  - Sarcasm Detection
  - Irony Detection

modality:
  - Text
  - Audio
  - Video

domain:
  - Political Vlogs
  - Multimodal Social Media Analysis
Method Overview
Video Input
   ├──► Text Extraction / Transcript Encoder
   ├──► Audio Feature Encoder
   ├──► Visual Feature Encoder
   └──► Multimodal Fusion Layer
              ├──► Sarcasm Classification Head
              └──► Irony Classification Head
Expected Repository Structure
sarcasmsense/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── data_exploration.ipynb
│   └── error_analysis.ipynb
├── src/
│   ├── preprocess_text.py
│   ├── preprocess_audio.py
│   ├── preprocess_video.py
│   ├── dataset.py
│   ├── model.py
│   ├── fusion.py
│   ├── train.py
│   ├── evaluate.py
│   └── utils.py
├── configs/
│   └── default.yaml
├── experiments/
│   └── README.md
├── results/
│   ├── confusion_matrix.png
│   ├── classification_report.csv
│   └── figures/
├── requirements.txt
└── LICENSE
Core Features
Multimodal sarcasm detection
Multitask sarcasm and irony classification
Political vlog understanding
Video, audio, and text-based feature extraction
Reproducible training and evaluation pipeline
Publication

SarcasmSense: A Novel Multitask Learning Framework for Vlog-Based Political Sarcasm and Irony Detection
Published in: IEEE Access
Year: 2026
DOI: 10.1109/ACCESS.2026.3674402

Citation
@article{islam2026sarcasmsense,
  title   = {SarcasmSense: A Novel Multitask Learning Framework for Vlog-Based Political Sarcasm and Irony Detection},
  author  = {Islam, Md. Shariful and Chowdhury, Md. Jalal Uddin and others},
  journal = {IEEE Access},
  year    = {2026},
  doi     = {10.1109/ACCESS.2026.3674402}
}
