# MRAN-VQA

## Multimodal Recursive Attention Network for Visual Question Answering

This repository contains research materials, code structure, and documentation for **MRAN-VQA: Multimodal Recursive Attention Network for Visual Question Answering**.

## Research Problem

Visual Question Answering requires a model to understand both:

- The visual content of an image
- The semantic meaning of a natural language question

The key challenge is to align image regions with question tokens so that the model can reason over the correct visual evidence.

---

## Research Objective

The objective of this project is to develop a **multimodal recursive attention network** that improves image-question reasoning by learning stronger cross-modal representations.

```yaml
task: Visual Question Answering
modality:
  - Image
  - Text
model_type:
  - Multimodal Attention Network
  - Vision-Language Model
  - Deep Learning
Method Overview

The MRAN-VQA framework is designed around:

Image feature extraction
Question embedding
Multimodal feature fusion
Recursive attention learning
Answer prediction
Image Input ──► Visual Encoder ──┐
                                  ├──► Recursive Attention Fusion ──► Classifier ──► Answer
Question ────► Text Encoder ──────┘
Expected Repository Structure
mran-vqa/
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   └── model_demo.ipynb
├── src/
│   ├── data_loader.py
│   ├── visual_encoder.py
│   ├── text_encoder.py
│   ├── attention.py
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
Vision-language feature fusion
Recursive attention mechanism
Visual question answering pipeline
Reproducible training and evaluation
Publication-aligned implementation structure
Publication

MRAN-VQA: Multimodal Recursive Attention Network for Visual Question Answering
Published in: Engineering Science and Technology, an International Journal
Year: 2025
DOI: 10.1016/j.jestch.2024.102232

Citation
@article{islam2025mranvqa,
  title   = {MRAN-VQA: Multimodal Recursive Attention Network for Visual Question Answering},
  author  = {Islam, Md. Shariful and Rony, Md. Abu Tareq and others},
  journal = {Engineering Science and Technology, an International Journal},
  year    = {2025},
  doi     = {10.1016/j.jestch.2024.102232}
}
