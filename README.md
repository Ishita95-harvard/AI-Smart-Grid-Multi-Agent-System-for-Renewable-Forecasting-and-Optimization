## [AI Smart Grid: Multi-Agent System for Renewable Forecasting and Optimization](https://github.com/Ishita95-harvad/Merged--AI-Smart-Grid-Modules-into-MAS-Grid-LAB-D-Simulation/tree/main) PHASE-I


**This repository contains the simulation code, forecasting models (LSTM, Prophet, ARIMA), and optimization workflow for an MAS-based Smart Grid architecture.**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12345678.svg)](https://doi.org/10.5281/zenodo.12345678)
![GitHub repo size](https://img.shields.io/github/repo-size/Ishita95-harvad/AI-Powered-Energy-Forecasting-Using-Multi-Agent-Systems-MAS-)
![GitHub last commit](https://img.shields.io/github/last-commit/Ishita95-harvad/AI-Powered-Energy-Forecasting-Using-Multi-Agent-Systems-MAS-)
![License](https://img.shields.io/github/license/Ishita95-harvad/AI-Powered-Energy-Forecasting-Using-Multi-Agent-Systems-MAS-)
![Python](https://img.shields.io/badge/python-3.10-blue.svg)
![Earth Engine](https://img.shields.io/badge/Data-Google%20Earth%20Engine-34A853?logo=google-earth)
![Google Cloud](https://img.shields.io/badge/Powered%20by-Google%20Cloud-blue?logo=google-cloud)
![TensorFlow](https://img.shields.io/badge/Built%20with-TensorFlow-FF6F00?logo=tensorflow)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ishita95-harvad/ai-smartgrid-mas/blob/main/notebooks/forecasting_lstm.ipynb)


![ertificate](https://github.com/Ishita95-harvad/-Simulation-Integration-ai-smart-grid-mas-/blob/main/figures/Screenshot%20(679).png)




### 1.[AI-Powered Multi-Agent System for Renewable Energy Forecasting](https://github.com/Ishita95-harvad/AI-Smart-Grid-Multi-Agent-System-for-Renewable-Forecasting-and-Optimization) 80.5%
### 2.[EXPERIMENTAL PERFORMANCE SET UP & MAS-Grid-LAB-D-SIMULATION OBSERVATAION - A Multi-Agent Reinforcement Learning Approach for Smart Grid Optimization and Real-Time Energy Management "](https://github.com/Ishita95-harvad/EXPERIMENTAL-SET-UP-MAS-Grid-LAB-D-SIMULATION)
This project demonstrates an AI-powered Multi-Agent System (MAS) designed for real-time energy forecasting, grid optimization, and climate-resilient decision-making.

## 🧠 Features
- 📈 **Hybrid Forecasting**: LSTM, Prophet, ARIMA ensemble
- 🤖 **Multi-Agent System**: Autonomous decision-making using RL
- ⚡ **GridLAB-D simulation and Optimization Algorithms**: MILP, GA, PPO for resource allocation
- 🌦 **Climate Resilience**: Weather-aware adaptive grid operations

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| `/notebooks` | Forecasting models in Jupyter |
| `/src` | MAS agent logic and optimization modules |
| `/data` | Sample weather and load data |
| `/simulation` | GridLAB-D config for simulation |
| `/models` | Pretrained models (if any) |
| `/figures` | Architecture diagrams |
| `/docs` | Paper summary and presentation slides |

## ✅ Final Folder Structure
```
ai-smart-grid-mas/
├── README.md                  <- Overview, architecture, features
├── LICENSE                    <- MIT/Apache license
├── .gitignore                 <- Ignore system and build files
├── requirements.txt           <- Python dependencies
├── environment.yml            <- Conda environment (optional)
├── CITATION.cff               <- Citation metadata for GitHub/Zenodo
├── setup.cfg                  <- linter/formatter settings
├── .github/
│   └── workflows/
│       └── deploy_docs.yml    <- GitHub Actions to deploy docs
├── notebooks/
│   ├── forecasting_lstm.ipynb <- LSTM forecasting notebook
│   ├── prophet_model.ipynb    <- Prophet-based forecasting
│   ├── anomaly_isolation.ipynb<- Anomaly detection
│   ├── optimization.ipynb     <- Pyomo optimization experiments
│   └── dashboard_eda.ipynb    <- Data exploration for dashboard
├── src/
│   ├── __init__.py
│   ├── agent.py               <- Agent definitions (forecast, anomaly, etc.)
│   ├── optimization.py        <- Pyomo-based optimization
│   ├── rl_agent.py            <- Smart agent using DQN/Policy Gradient
│   ├── communication.py       <- Inter-agent messaging logic
│   └── utils.py               <- Shared utilities
├── data/
│   ├── raw/                   <- Raw data files
│   ├── processed/             <- Cleaned datasets
│   └── metadata.json          <- Description of datasets
├── models/
│   ├── lstm_model.pt          <- Trained LSTM model
│   ├── prophet_model.pkl      <- Prophet model dump
│   └── rl_policy.h5           <- Reinforcement learning policy
├── app/
│   ├── app.py                 <- Streamlit dashboard UI
│   ├── dashboard_utils.py     <- Plotting & logic
│   └── assets/                <- Images/icons used in dashboard
├── docs/
│   ├── index.md               <- GitHub Pages landing page
│   ├── architecture.md        <- System design, agent roles
│   ├── simulation.md          <- Experimental setup and results
│   ├── figures/
│   │   ├── architecture.png
│   │   ├── co2_savings_chart.png
│   │   └── load_forecast_accuracy.png
│   └── .nojekyll              <- Disable Jekyll for docs
├── publication/
│   ├── manuscript_IEEE.docx   <- Final formatted manuscript
│   ├── abstract.txt
│   ├── author_declaration.pdf
│   ├── plagiarism_report.pdf
│   └── cover_letter.txt
└── deploy/
    ├── Dockerfile             <- Optional containerized deployment
    ├── azure_functions/       <- Azure API deployable functions
    ├── streamlit_share/       <- Streamlit app deploy folder
    └── zenodo.json            <- Metadata for Zenodo DOI

````

## 🔗 Related Resources

- 📜 [Research Paper UGC recognised (Preprint)](link_to_preprint.pdf)
- 📊 [Live Streamlit Dashboard (if deployed)](link_here)
- 📘 [Dataset DOI on Zenodo](https://doi.org/10.5281/zenodo.xxxxxx)







