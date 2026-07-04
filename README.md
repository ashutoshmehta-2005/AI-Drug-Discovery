# 🧬 AI-Drug-Discovery

An AI-powered Drug Discovery Platform that accelerates the identification of promising antiviral drug candidates using Machine Learning, RDKit, and Explainable AI.

---

## 📖 Project Overview

Traditional drug discovery is a time-consuming and expensive process that requires researchers to experimentally test thousands of molecules before finding an effective drug candidate.

This project aims to reduce this effort by using Artificial Intelligence to computationally analyze candidate molecules and predict their potential effectiveness against viral diseases.

Researchers can upload molecular structures in SMILES format, and the platform extracts molecular features using RDKit, evaluates them using multiple Machine Learning models, ranks the best candidates, and provides AI-generated explanations for each prediction.

---

## 🎯 Objectives

- Accelerate viral drug discovery
- Reduce laboratory testing cost
- Predict promising drug candidates
- Improve decision making using Explainable AI
- Provide an interactive dashboard for researchers

---

## 🚀 Features

- Secure Researcher Login
- Viral Disease Selection
- Target Protein Identification
- SMILES Molecule Upload
- Molecular Descriptor Extraction using RDKit
- Machine Learning Prediction
- Drug-likeness Prediction
- Toxicity Prediction
- ADMET Evaluation
- Drug Candidate Ranking
- AI-based Explanation
- Interactive Dashboard
- PDF Report Generation

---

## 🧠 Machine Learning Models

- Random Forest
- XGBoost
- Logistic Regression

The system compares predictions from multiple models to improve reliability and confidence.

---

## ⚙️ Tech Stack

### Frontend
- React.js

### Backend
- Flask (Python)

### Machine Learning
- Scikit-Learn
- XGBoost

### Cheminformatics
- RDKit

### Database
- MySQL

### Authentication
- JWT Authentication

### PDF Generation
- ReportLab

---

## 🔄 Project Workflow

Researcher Login

↓

Disease Selection

↓

Target Protein Identification

↓

Upload Molecule (SMILES)

↓

RDKit Feature Extraction

↓

Feature Preprocessing

↓

Machine Learning Prediction

↓

Drug Evaluation

↓

Candidate Ranking

↓

LLM-based Explanation

↓

Dashboard

↓

PDF Report

---

## 📊 Prediction Parameters

The platform evaluates candidate molecules based on:

- Predicted Binding Score
- Drug-likeness
- Toxicity
- ADMET Properties
- Confidence Score

---

## 📂 Project Structure

AI-Drug-Discovery/

├── frontend/

├── backend/

├── ml_model/

├── database/

├── datasets/

├── docs/

├── reports/

└── README.md

---

## 👨‍💻 Team Members

(To be updated)

---

## 🔮 Future Scope

- Deep Learning-based Drug Prediction
- Molecular Docking Integration
- Real-time ChEMBL/PubChem Integration
- Generative AI for Novel Drug Design
- Cloud Deployment

---

## 📜 License

This project is developed for educational and research purposes.
