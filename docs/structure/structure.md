---
title: Structure
layout: default
nav_order: 2
---
<h2>Project Structure</h2>

The repository organization was designed for clarity and modularity.
```bash
preditor_precos_imobiliarios/
├── .github/
│ └── workflows/
│ ├── deploy.yml           # GitHub Actions for automated deployment
│ └── tests.yml            # GitHub Actions for automated tests
│
├── tests/                 # Automated tests
│ ├── e2e/                 # End-to-end tests (login, authentication, etc.)
│ │ ├── test_login_falha.py
│ │ └── test_login_sucesso.py
│ └── unit/                # Unit tests (isolated functions and modules)
│ └── test_app.py
│
├── venv/                  # Local virtual environment (not versioned)
│ ├── Lib/
│ ├── Scripts/
│ └── pyvenv.cfg
│
├── app.py                 # Main application (Streamlit + MFA authentication)
├── csv_unico.csv          # Consolidated database (price history)
├── modelos_sarima.joblib  # Pre-trained SARIMA models
│
├── LICENSE                # MIT License of the project
├── README.md # Main documentation (this file)
└── requirements.txt       # Project dependencies (pip)


```
