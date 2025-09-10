---
title: Tools
parent: Technologies and Tools Used
nav_order: 1
layout: default
---

Main Libraries:

Streamlit (web framework for creating the dashboard interface quickly and Pythonically),

Plotly (interactive data visualization in graphs, built into Streamlit),

Pandas (tabular data manipulation and analysis),

PyTest and Selenium (used for automated testing of the application and interface).

Jupyter Notebook: Environment used for initial exploration and data cleansing.

Infrastructure: Terraform for describing the infrastructure in code, provisioning AWS services (especially EC2 for hosting the app).

Cloud Platform: AWS EC2 – a virtual machine in the cloud where the Streamlit dashboard can run continuously for end-user access.

CI/CD: GitHub Actions – a pipeline configured to integrate and eventually deploy the project automatically (build, test, and deploy). This ensures quality and agility in deliveries.

Version Control: Git & GitHub – team collaboration and versioning of all source code, notebooks and infrastructure, allowing traceability of contributions and parallel work via branches.

![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-orange?logo=streamlit)
![Plotly](https://img.shields.io/badge/Charts-Plotly-lightgrey?logo=plotly)
![Terraform](https://img.shields.io/badge/Terraform-Used-5f43e9?logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-EC2-informational?logo=amazon-aws&logoColor=white&color=232F3E)
![CI/CD](https://img.shields.io/github/actions/workflow/status/cjomode/preditor_precos_imobiliarios/deploy.yml?label=CI%2FCD&logo=github)
![MFA](https://img.shields.io/badge/🔐_MFA-Ativado-success)
![Pytest](https://img.shields.io/badge/Testes-Pytest-yellow?logo=pytest)
![Selenium](https://img.shields.io/badge/Testes%20UI-Selenium-43B02A?logo=selenium&logoColor=white)