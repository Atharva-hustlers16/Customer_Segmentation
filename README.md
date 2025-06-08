<!-- -------------------------------------------------------------------- -->
<!--                     CUSTOMER SEGMENTATION – README                   -->
<!-- -------------------------------------------------------------------- -->

<h1 align="center">🛍️ Customer Segmentation & Spender-Class App</h1>
<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.9+-3776AB?logo=python&logoColor=white">
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-1.x-E43E36?logo=streamlit&logoColor=white">
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg">
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
  <img alt="Build" src="https://img.shields.io/badge/Status-active-success">
</p>

> **Predict whether a customer is a _High_ or _Low_ spender in a single click — powered by RFM features, Logistic Regression and a dark-themed Streamlit dashboard.**

---



---

## 📋 Table of Contents
1. [Features](#-features)  
2. [Dataset](#-dataset)  
3. [Quick Start](#-quick-start)  
  

---

## ✨ Features
- **Exploratory Data Analysis** & visualisations in a Jupyter Notebook  
- **RFM Feature Engineering** (Recency, Frequency, Monetary) for behavioural insight  
- **Logistic Regression** model with standardisation and train/test split  
- **Interactive Streamlit App**:  
  - Dark-mode UI with custom-styled widgets  
  - Side-panel charts (class balance, monetary distribution, recency box-plot)  
  - Real-time probability & accuracy read-outs  
- **One-click Deployment**: run locally or on any Streamlit-compatible host (e.g. Streamlit Cloud, Hugging Face Spaces)

---

## 🗄️ Dataset
- **Name:** Online Retail (2010-2011) – UK e-commerce transactional data  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online%2Bretail)  
- **Size:** 541 k rows × 8 columns (`InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, …)  
- **Licence:** For research/educational use

> The raw file `Online Retail.xlsx` is provided for convenience; consider replacing it with a download script for larger-scale usage.

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/Atharva-hustlers16/Customer_Segmentation.git
cd Customer_Segmentation

# 2. Create virtual env (recommended)
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Explore the notebook
jupyter lab CustomerLogistic.ipynb

# 5. Run the Streamlit app
streamlit run app.py
