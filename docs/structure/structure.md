---
title: Structure
layout: default
nav_order: 2
---
<h2>Project Structure</h2>

The repository organization was designed for clarity and modularity.
```bash
preditor_precos_imobiliarios/
├── data/                  # Processed real estate data (sales and rentals)
├── db/                    # Local databases and preprocessed models
├── infra/                 # Infrastructure as code (Terraform + user_data.sh)
│   ├── main.tf
│   ├── outputs.tf
│   ├── user_data.sh
│   └── variables.tf
├── notebooks/             # EDA and model development notebooks
├── script/                # Auxiliary scripts for data processing and ML
├── tests/                 # Automated tests
│   ├── e2e/               # End-to-end tests
│   │   ├── test_login_falha.py
│   │   └── test_login_sucesso.py
│   └── unit/              # Unit tests
│       └── test_app.py
├── .github/               
│   └── workflows/
│       └── deploy.yml     # GitHub Actions for automated deployment
│       └── tests.yml      # GitHub Actions for automated testing
├── .gitignore             # Ignore sensitive files and build directories
├── app.py                 # Main app code with MFA + dashboard
├── LICENSE                # MIT License project
├── README.md              # Project documentation (you are here!)
└── requirements.txt       # Project dependencies (pip)

```