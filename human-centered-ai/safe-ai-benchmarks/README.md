# Safe AI Benchmarks

## Benchmark Templates for Responsible, Robust, and Human-Centered AI Systems

This repository is designed for organizing benchmarks that evaluate AI systems beyond accuracy, including robustness, fairness, explainability, safety, calibration, reproducibility, and real-world failure cases.

## Research Motivation

AI systems used in healthcare, social platforms, robotics, and human-facing applications must be evaluated for more than predictive performance.

A safety-aware benchmark should assess:

- Accuracy
- Robustness
- Bias and fairness
- Explainability
- Calibration
- Failure modes
- Reproducibility
- Human-centered risks

---

## Research Objectives

```yaml
objectives:
  - Build reusable AI safety benchmark templates
  - Evaluate models under realistic distribution shifts
  - Measure robustness against noise and missing data
  - Analyze fairness across subgroups
  - Document explainability and failure cases
  - Support reproducible model comparison
  - Provide publication-ready benchmark reporting
Benchmark Categories
benchmark_categories:
  robustness:
    - Noise sensitivity
    - Missing data robustness
    - Domain shift evaluation
    - Adversarial perturbation analysis

  fairness:
    - Subgroup performance
    - Class imbalance analysis
    - Bias inspection
    - Equal error rate comparison

  explainability:
    - SHAP
    - LIME
    - Grad-CAM
    - Feature attribution stability

  reliability:
    - Calibration
    - Confidence analysis
    - Uncertainty estimation
    - False positive and false negative analysis

  reproducibility:
    - Fixed seeds
    - Config-driven experiments
    - Standard train/validation/test splits
    - Version-controlled results
Expected Repository Structure
safe-ai-benchmarks/
├── README.md
├── benchmarks/
│   ├── classification/
│   ├── medical-ai/
│   ├── nlp/
│   ├── multimodal-ai/
│   └── robotics/
├── data/
│   ├── sample/
│   └── README.md
├── notebooks/
│   ├── benchmark_demo.ipynb
│   ├── robustness_analysis.ipynb
│   ├── fairness_analysis.ipynb
│   └── calibration_analysis.ipynb
├── src/
│   ├── data_checks.py
│   ├── split_checks.py
│   ├── leakage_checks.py
│   ├── metrics.py
│   ├── robustness.py
│   ├── fairness.py
│   ├── calibration.py
│   ├── explainability.py
│   ├── report_generator.py
│   └── utils.py
├── configs/
│   ├── benchmark_config.yaml
│   └── model_config.yaml
├── results/
│   ├── metrics/
│   ├── robustness/
│   ├── fairness/
│   ├── calibration/
│   └── reports/
├── docs/
│   ├── benchmark_protocol.md
│   ├── reporting_template.md
│   ├── reproducibility_checklist.md
│   └── model_card_template.md
├── tests/
│   ├── test_data_splits.py
│   ├── test_metrics.py
│   └── test_no_leakage.py
├── requirements.txt
├── LICENSE
└── .gitignore
Benchmark Workflow
Dataset
  │
  ▼
Data Integrity Checks
  │
  ├── Missing Values
  ├── Duplicate Samples
  ├── Label Distribution
  └── Leakage Risk
  │
  ▼
Train / Validation / Test Split
  │
  ▼
Model Training
  │
  ▼
Standard Evaluation
  │
  ├── Accuracy
  ├── Precision
  ├── Recall
  ├── F1-score
  └── AUC
  │
  ▼
Safety Evaluation
  │
  ├── Robustness
  ├── Fairness
  ├── Calibration
  ├── Explainability
  └── Failure Cases
  │
  ▼
Benchmark Report
Metrics
standard_metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Macro-F1
  - Weighted-F1
  - AUC

robustness_metrics:
  - Performance under noise
  - Performance under missing features
  - Domain shift performance
  - Perturbation sensitivity

fairness_metrics:
  - Subgroup accuracy
  - Subgroup F1-score
  - Equal opportunity difference
  - False positive rate difference
  - False negative rate difference

calibration_metrics:
  - Expected Calibration Error
  - Brier Score
  - Reliability Diagram

explainability_outputs:
  - Feature importance
  - SHAP values
  - LIME explanations
  - Grad-CAM maps
  - Error case explanations
Publication-Risk Checks
critical_checks:
  - Verify train/validation/test split before preprocessing
  - Ensure no duplicate samples across splits
  - Fit scalers, encoders, imputers, and feature selectors only on training data
  - Prevent patient-level or subject-level leakage
  - Report class distribution in every split
  - Use the same test set across model comparisons
  - Avoid tuning hyperparameters on the test set
  - Include baseline models
  - Include ablation studies
  - Report limitations clearly
Example Benchmark Report Template
# Benchmark Report


Md Shariful Islam
Google Scholar: https://scholar.google.com/citations?user=-Rut6DAAAAAJ&hl=en
