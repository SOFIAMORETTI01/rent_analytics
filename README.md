# 🏡 CABA rental market analysis

This project collects rental listings from Argenprop, processes the data, and delivers key insights through interactive Power BI visualizations.

It focuses on rental prices, expenses, and apartment features across neighborhoods in Capital Federal (CABA).

---

## 🚀 Tech Stack

- 🐍 Python: `selenium`, `pandas`, `webdriver-manager`
- 📊 Visualization: Power BI
- 🌍 Source: [argenprop.com](https://www.argenprop.com/)

---

## 🚀 Why this project?

This scraper enables custom data pipelines to:

- Analyze rental trends.
- Compare prices per m2 across neighborhoods.
- Detect underpriced or overpriced listings.
- Build dashboards or machine learning models based on housing data.

---

## 🌐 View Online

[![View Dashboard](https://img.shields.io/badge/🔎%20View%20Dashboard%20Online-blue?style=for-the-badge)](https://app.powerbi.com/view?r=eyJrIjoiYzUwZGIxZDctYjgzOC00YmI3LWExZWYtZmJjY2RjMDk1NTJiIiwidCI6IjNlMDUxM2Q2LTY4ZmEtNDE2ZS04ZGUxLTZjNWNkYzMxOWZmYSIsImMiOjR9)

---

## 🛠️ How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/SOFIAMORETTI01/rent_analytics.git
   cd rent_analytics

2. **Install dependencies:**
   pip install -r requirements.txt

3. **Run scripts:**
   python script/scrape_argenprop.py
   python script/scrape_argenprop_clustering.py
