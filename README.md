# 🤖 OmniML — Autonomous Human-in-the-Loop AutoML Platform

> **OmniML** is an AI-powered autonomous machine learning platform that automates the complete ML lifecycle using a multi-agent LangGraph workflow. From dataset analysis and model training to hyperparameter optimization, explainability, and report generation, OmniML acts as an intelligent Machine Learning Engineer while keeping humans in control through interactive dashboards.

---

## ✨ Features

### 🧠 Multi-Agent AI Workflow

Powered by **LangGraph**, OmniML orchestrates multiple specialized agents to automate machine learning tasks:

* Automated Dataset Analysis
* Exploratory Data Analysis (EDA)
* Model Training
* Hyperparameter Optimization
* Explainable AI Insights
* Report Generation

---

### 📊 Interactive EDA Dashboard

Automatically generates:

* Missing Value Analysis
* Feature Statistics
* Data Distributions
* Correlation Heatmaps
* Outlier Detection
* AI-Powered Dataset Insights

---

### ⚙️ Hyperparameter Tuning Console

Optimize model performance through:

* Learning Rate Search
* Batch Size Optimization
* Epoch Tuning
* Optimizer Selection
* Experiment Tracking

---

### 🤖 Autonomous Training Engine

Supports:

* PyTorch
* Scikit-Learn
* XGBoost

Features:

* Automated Data Preparation
* Model Training
* Validation
* Metrics Tracking
* Performance Monitoring

---

### 🔍 Explainable AI

Generate meaningful insights about:

* Dataset Characteristics
* Feature Importance
* Model Performance
* Training Behavior

---

### 📄 Automated Reporting

Produce professional reports including:

* Dataset Summary
* EDA Findings
* Training Results
* Model Evaluation
* Performance Metrics

---

### 🎨 Human-in-the-Loop (HITL)

OmniML combines automation with user control.

#### Visual Model Builder

* Drag-and-drop architecture design
* React Flow integration
* Interactive model editing

#### Training Configuration Dashboard

Configure:

* Epochs
* Learning Rate
* Batch Size
* Optimizers
* Validation Split

without writing code.

#### Live Training Console

Monitor:

* Training Logs
* Metrics
* Runtime Information
* Model Progress

in real time.

---

## 🏗 Architecture

```text
User Prompt
      │
      ▼
Chainlit Interface
      │
      ▼
LangGraph Orchestrator
      │
 ┌────┼────┬────┬────┐
 ▼    ▼    ▼    ▼    ▼
EDA  HPT  ML  Explain Report
      │
      ▼
Training Engine
      │
      ▼
Results & Reports
```

---

## 📁 Project Structure

```text
OMNIML/
│
├── anomallm/
│   ├── __init__.py
│   ├── detector.py
│   ├── explainer.py
│   ├── persistence.py
│   ├── reporter.py
│   └── trainer.py
│
├── public/
│   ├── eda_dashboard/
│   ├── hpt_console/
│   ├── react_flow_editor/
│   ├── training_config/
│   ├── training_console/
│   ├── custom.js
│   └── style.css
│
├── app.py
├── graph.py
├── tools.py
├── start.py
├── chainlit.md
├── Dockerfile
├── requirements.txt
├── setup.py
├── README.md
└── .gitignore
```

---

## 🛠 Tech Stack

| Category                    | Technology          |
| --------------------------- | ------------------- |
| Agent Orchestration         | LangGraph           |
| LLM Backend                 | Groq GPT-OSS-120B   |
| Frontend                    | Chainlit            |
| Deep Learning               | PyTorch             |
| Machine Learning            | Scikit-Learn        |
| Gradient Boosting           | XGBoost             |
| Hyperparameter Optimization | Optuna              |
| Visualization               | Matplotlib, Seaborn |
| Persistence                 | SQLite              |
| Deployment                  | Docker              |

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/omniml.git
cd omniml
```

### Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
CHAINLIT_AUTH_SECRET=your_secret
```

### Launch OmniML

```bash
python start.py
```

Open:

```text
http://localhost:8001
```

---

## 🔄 Workflow

```text
User Problem
      │
      ▼
Dataset Analysis
      │
      ▼
EDA Generation
      │
      ▼
Training Configuration
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Optimization
      │
      ▼
Explainability Analysis
      │
      ▼
Report Generation
      │
      ▼
Final Results
```

---

## 🎯 Use Cases

* Disease Prediction
* Fraud Detection
* House Price Prediction
* Customer Churn Prediction
* Demand Forecasting
* Student Performance Analysis
* Research Prototyping

---

## 📅 Roadmap

* [ ] Multi-GPU Training
* [ ] Cloud Execution Support
* [ ] Computer Vision Pipelines
* [ ] NLP Pipelines
* [ ] Time Series Forecasting
* [ ] Research Benchmarking
* [ ] Auto Deployment to AWS/GCP/Azure

---

## 🌟 Why OmniML?
* Autonomous ML Workflow
* Multi-Agent Architecture
* Interactive Dashboards
* Explainable AI
* Human-in-the-Loop Controls
* Automated Reporting
* Production-Oriented Design

OmniML transforms machine learning from a manual engineering process into an intelligent, collaborative AI workflow.
