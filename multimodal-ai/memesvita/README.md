# MemesViTa

## Multimodal Fusion for Troll Meme Identification

This repository is for **MemesViTa**, a multimodal AI project focused on identifying troll memes through visual and textual understanding.

## Research Problem

Memes often combine images and text to express humor, sarcasm, misinformation, hate, political messaging, or trolling behavior.

A model that only analyzes text or image separately may fail to understand the actual meaning of a meme.

---

## Research Objective

The objective of this project is to build a multimodal fusion framework for troll meme identification by jointly analyzing:

- Meme image
- Embedded text
- Visual context
- Text-image relationship
- Semantic incongruity

```yaml
task:
  - Troll Meme Identification
  - Multimodal Classification

modality:
  - Image
  - Text

domain:
  - Social Media
  - Meme Understanding
  - Multimodal Content Moderation
Method Overview
Meme Image ──► Visual Encoder ──────┐
                                    ├──► Multimodal Fusion ──► Classifier ──► Troll / Non-Troll
OCR Text ────► Text Encoder ────────┘
Expected Repository Structure
memesvita/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── dataset_analysis.ipynb
│   └── prediction_demo.ipynb
├── src/
│   ├── ocr.py
│   ├── image_preprocessing.py
│   ├── text_preprocessing.py
│   ├── visual_encoder.py
│   ├── text_encoder.py
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
│   ├── figures/
│   └── tables/
├── requirements.txt
└── LICENSE
Core Features
Meme image and OCR text processing
Vision-language feature fusion
Troll meme classification
Multimodal social media analysis
Explainable meme understanding pipeline
Research Applications
Social media content moderation
Harmful meme detection
Political meme analysis
Online safety
Human-centered AI systems
Publication

MemesViTa: A Novel Multimodal Fusion Technique for Troll Memes Identification
Year: 2024

Add final venue, DOI, PDF, and code links after confirmation.

Citation
@article{sultan2024memesvita,
  title   = {MemesViTa: A Novel Multimodal Fusion Technique for Troll Memes Identification},
  author  = {Sultan, Tipu and Rony, Abu Tareq and Islam, Md. Shariful and others},
  year    = {2024},
  note    = {Add venue and DOI after confirmation}
}
