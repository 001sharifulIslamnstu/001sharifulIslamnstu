# Nirbhoy Platform

## Human-Centered AI Platform for Technology-Facilitated Violence Response

This repository contains the project structure and documentation for **Nirbhoy**, a human-centered AI platform designed to support prevention, reporting, and response workflows for technology-facilitated violence against women.

## Project Motivation

Technology-facilitated violence can involve harassment, blackmail, cyber abuse, digital threats, privacy violations, and other forms of online harm. Survivors often need a safe, structured, and accountable way to report incidents, preserve evidence, and receive support.

The Nirbhoy platform is designed to provide a structured reporting and case-management workflow with AI-assisted sensitivity scoring, evidence handling, report generation, and authority-side monitoring.

---

## Core Objectives

```yaml
objectives:
  - Provide a survivor-centered reporting workflow
  - Support secure evidence upload and case documentation
  - Generate structured PDF reports
  - Assist case prioritization using AI-based sensitivity scoring
  - Provide authority dashboard and case-management tools
  - Support independent audit workflows
  - Track SLA, escalation, and response history
  - Add tamper-evident logging through dummy blockchain architecture
Key Features
Multi-step survivor reporting wizard
Evidence upload module
AI-based case sensitivity scoring
PDF report generation
Authority case-management dashboard
Independent audit team workflow
SLA tracking
Escalation logs
Tamper-evident dummy blockchain storage
Optional local LLM integration using Ollama
System Overview
User / Survivor
      │
      ▼
Multi-Step Reporting Wizard
      │
      ├──► Evidence Upload
      ├──► Incident Details
      ├──► AI Sensitivity Scoring
      └──► PDF Report Generation
                    │
                    ▼
Authority Dashboard
      │
      ├──► Case Review
      ├──► SLA Tracking
      ├──► Escalation Logs
      └──► Audit Team Workflow
                    │
                    ▼
Tamper-Evident Case Log
Expected Repository Structure
nirbhoy-platform/
├── README.md
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── models/
│   │   ├── services/
│   │   ├── utils/
│   │   └── main.py
│   ├── tests/
│   └── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── assets/
│   └── package.json
├── ai/
│   ├── sensitivity_scoring/
│   ├── prompt_templates/
│   ├── ollama_integration/
│   └── evaluation/
├── docs/
│   ├── system_design.md
│   ├── data_flow.md
│   ├── privacy_and_safety.md
│   ├── deployment.md
│   └── user_workflow.md
├── reports/
│   ├── templates/
│   └── generated_examples/
├── audit/
│   ├── sla_tracking.md
│   ├── escalation_policy.md
│   └── audit_workflow.md
├── blockchain_dummy/
│   ├── hash_logger.py
│   └── verification.py
├── docker-compose.yml
├── LICENSE
└── .gitignore
AI Component
ai_module:
  name: Case Sensitivity Scoring
  input:
    - Incident description
    - Threat severity indicators
    - Evidence metadata
    - Report context
  output:
    - Sensitivity score
    - Priority level
    - Recommended escalation flag
  caution:
    - AI should support decision-making, not replace human review.
    - Human oversight is required for sensitive cases.
Safety and Ethics

This project must be designed with strong attention to:

Survivor privacy
Secure evidence handling
Consent-aware data collection
Human oversight
Bias and fairness
Explainable AI scoring
Responsible escalation
Non-harmful language generation
Auditability and accountability
Suggested Evaluation
evaluation:
  usability:
    - Reporting completion rate
    - User workflow clarity
    - Time to submit report

  ai_model:
    - Sensitivity classification accuracy
    - False negative rate
    - False positive rate
    - Human reviewer agreement

  system:
    - Case response time
    - SLA compliance
    - Escalation accuracy
    - Audit log integrity
Technology Stack
backend:
  - Python
  - Django or FastAPI
  - REST API

frontend:
  - HTML
  - CSS
  - JavaScript
  - React or Django Templates

ai:
  - Python
  - scikit-learn
  - Transformers
  - Local LLM with Ollama

database:
  - PostgreSQL
  - SQLite for prototype

documentation:
  - Markdown
  - PDF generation
Status
status:
  project_type: Human-Centered AI Platform
  domain: AI for Social Good
  stage: Prototype / Research System
  reproducibility: In Progress
