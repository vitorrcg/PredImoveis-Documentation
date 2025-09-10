---
title: Installation
layout: default
nav_order: 3
---
<h2> Local Installation and Execution </h2>

Follow the steps below to run the project locally in your development environment:
<br>

##### 1. Clone the repository:
```bash
git clone https://github.com/cjomode/preditor_precos_imobiliarios.git
```
Go into the project directory: cd preditor_precos_imobiliarios.

##### 2. Create a virtual environment (optional, but recommended):
```bash
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

##### 3. Install the dependencies:
```bash
pip install -r requirements.txt
```
Make sure all libraries are installed correctly.

##### 4. Execute the Streamlit application
```bash
streamlit run app.py
```
This will start the local Streamlit server. The console will display a URL (by default http://localhost:8501) – open this address in your web browser.

##### 5. Use the dashboard: When you access the app, you'll be presented with the MFA login screen. Enter your login credentials and the two-factor authentication code (as configured) to log in.
<br>
Once authenticated, you can browse interactive charts and view appreciation/depreciation forecasts for different cities and scenarios.