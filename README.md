# 🏠 Airbnb Web Scraping Analysis & EDA

This repository contains a comprehensive project developed during my internship at **CodeAlpha**. It involves **web scraping** data from Airbnb listings, followed by **data cleaning**, **exploratory data analysis (EDA)**, and deriving key insights about rental trends.

---

## 📌 Project Overview

The main objective of this project is to:
- Scrape Airbnb listings from the web (Cairo, Egypt).
- Extract useful features such as **price, location, rating, description, and host details**.
- Handle data inconsistencies, currency formats, and missing values.
- Perform **Exploratory Data Analysis** to uncover patterns and trends.
- Visualize insights using charts and plots.

---

## 🔧 Tech Stack

- **Python**
- `requests`, `BeautifulSoup` – for web scraping
- `pandas`, `numpy` – for data manipulation
- `matplotlib`, `seaborn`, `plotly` – for data visualization
- `re` – for regular expressions and text processing

---

## 📂 Project Structure

```bash
airbnb-scraping-eda/
│
├── 📁 data/                  # Raw and cleaned datasets
│
├── 📁 notebooks/             # Jupyter Notebooks for scraping and EDA
│   ├── 01_scraping.ipynb
│   └── 02_eda.ipynb
│
├── 📁 images/                # Visualizations used in the analysis
│
├── main.py                  # Scraping script (if applicable)
├── requirements.txt         # List of required packages
├── README.md                # This file
└── LICENSE
