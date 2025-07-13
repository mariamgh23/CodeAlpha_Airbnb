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

🚀 Key Features
Scrapes multiple pages of Airbnb listings.

Handles currency symbols, discounts, and incomplete data.

Converts textual information (like "5 nights for EGP 2000") into structured columns.

Performs EDA on:

Price distribution

Ratings vs. price

Most common locations

Discounts and sales impact

Uses exception handling for robust scraping.

📊 Sample Insights
Average Airbnb price in Cairo

Correlation between price and rating

Popular areas and average costs

Listing types and their frequency

📎 How to Run
Clone the repo:
git clone https://github.com/yourusername/airbnb-scraping-eda.git
cd airbnb-scraping-eda

Install dependencies:
pip install -r requirements.txt

Run the scraping script:
python main.py

Explore the data with:
jupyter notebook notebooks/02_eda.ipynb




🙏 Acknowledgements
Special thanks to CodeAlpha for the opportunity and guidance throughout the internship.

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

📬 Contact
Mariam Ghareeb
📧 mariamghareeb376@gmail.com
🔗 LinkedIn:https://www.linkedin.com/in/mariam-ghareeb
📊 Kaggle:https://www.kaggle.com/mariamelghareeb




