# 💸 AI-Powered Personal Finance Tracker

Track smarter. Spend wiser. An intelligent, OOP-based personal finance manager built with Python.

---

## 🧠 Overview

This project is an advanced **Python-based personal finance tracker** that uses **object-oriented programming principles** and **AI-powered analytics** to help users:

- Manage expenses and budgets
- Automatically categorize transactions
- Predict future spending trends
- Visualize financial health

It’s like having a pocket-sized financial analyst — but nerdier. 😎

---

## 📦 Features

✅ Object-Oriented Architecture  
✅ Command-Line Interface (CLI) with [Typer](https://typer.tiangolo.com/)  
✅ SQLite-powered persistent data storage  
✅ ML integration with `scikit-learn` (KMeans clustering)  
✅ Graphs and trend analysis with `matplotlib`  
✅ Budget tracking and balance calculator  
✅ Easy-to-extend and modular codebase

---

## 🧱 Project Structure

personal_finance_tracker/
├── main.py
├── config.py
├── models/
│ ├── transaction.py
│ ├── user_profile.py
│ └── category.py
├── services/
│ ├── transaction_service.py
│ ├── analytics_service.py
│ └── ml_service.py
├── cli/
│ └── commands.py
├── database/
│ ├── db.py
│ └── seed_data.py
├── utils/
│ ├── logger.py
│ └── helpers.py
└── README.md
