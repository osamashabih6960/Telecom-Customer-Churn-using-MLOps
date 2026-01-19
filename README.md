# Telecom-Customer-Churn-Prediction


# **🚀 End-to-End MLOps Project – Production-Grade ML Pipeline**

This repository contains a fully modular, enterprise-grade **MLOps architecture** demonstrating industry-standard practices for building, training, deploying, and maintaining Machine Learning systems.

The project implements a complete ML lifecycle including:

* 🧱 Project Scaffolding & Environment Setup
* 🍃 **MongoDB Atlas** for cloud-hosted data storage
* 📑 Logging, Exception Handling & Notebooks
* 📥 Data Ingestion
* 🛡️ Data Validation
* 🔄 Data Transformation
* 🤖 Model Training
* 📊 Model Evaluation & Model Registry on **AWS S3**
* 🚀 Model Deployment with **Docker + ECR + EC2 + GitHub Actions CI/CD**
* 📡 Prediction Pipeline + Web App

This README walks through the full workflow and highlights the tools & engineering practices used — ideal for hiring managers reviewing the project.

---

# **📂 1. Project Setup & Environment**

### **1.1 Generate Project Template**

```bash
python template.py
```

### **1.2 Add Local Package Configuration**

Configured using:

* `setup.py`
* `pyproject.toml`

(Refer to crashcourse.txt for deep explanations.)

### **1.3 Create Virtual Environment**

```bash
python -m venv venv
venv\Scripts\activate    # Windows
source venv/bin/activate # Mac/Linux
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Verify local packages:

```bash
pip list
```

---
