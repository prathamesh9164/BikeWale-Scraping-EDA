# 🏍️ BikeWale Motorcycle EDA — Indian Market Analysis 2024

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Plotly](https://img.shields.io/badge/Plotly-Interactive_Charts-3F4F75.svg)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web_Scraping-green.svg)
![HTML/CSS/JS](https://img.shields.io/badge/Dashboard-Vanilla_Web_Stack-orange.svg)

An end-to-end data science pipeline — **418 motorcycles** scraped live from BikeWale.com, cleaned, engineered, and analysed through 50+ interactive visualisations. From ₹47k commuters to ₹1 Crore superbikes — every segment, every pattern, uncovered.

*Project completed as part of the Data Science curriculum at Innomatics Research Labs.*

---

## 🌟 Project Overview

This repository contains the complete workflow for extracting, cleaning, exploring, and visualizing the Indian motorcycle market data. The project culminates in a **fully custom, interactive web dashboard** (`main.html`) built from scratch without any heavy web frameworks.

### ✨ Highlights
- **Web Scraping:** Extracted real-time data of 418 motorcycle models across 15+ brands from BikeWale.
- **Data Cleaning & EDA:** Handled missing values, engineered new features (price categories, engine segments), and analyzed correlations.
- **Visual Analytics:** Generated 50+ charts (Univariate, Bivariate, Multivariate) to uncover hidden market patterns.
- **Interactive Dashboard:** A stunning, responsive UI displaying key KPIs, a unified dashboard view, and a categorized visualization gallery.

---

## 📊 Key Findings

1. **Price Distribution is Heavily Right-Skewed:** The majority of motorcycles fall in the ₹50k–₹1.5L range. Superbike outliers push the mean (₹6.95L) far above the median (₹1.99L).
2. **Engine Capacity is the Strongest Price Predictor:** With a Pearson r = 0.77, engine displacement predicts price better than any other variable.
3. **Four Distinct Market Segments Emerge:** Commuters, mid-range tourers, adventure/cruisers, and performance superbikes form distinct clusters based on price, engine, and mileage.
4. **Brand Portfolio Signals:** Most brands specialize in 1–2 price tiers. Bajaj dominates by reviews; Ducati commands the highest average price; consumer satisfaction (ratings) remains relatively stable across all segments.

---

## 🛠️ Technology Stack

- **Data Scraping:** `BeautifulSoup`, `requests` (`Final_Scrapping.ipynb`)
- **Data Processing & EDA:** `pandas`, `numpy`, `matplotlib`, `seaborn` (`Final_Scrapping_EDA.ipynb`, `motorcycle_eda.ipynb`)
- **Visualization:** `plotly` (`Final_Scrapping_Visualization.ipynb`)
- **Dashboard UI:** HTML5, CSS3 (Custom Variables, CSS Grid/Flexbox), Vanilla JavaScript, `Chart.js` (`main.html`)

---

## 🚀 How to Explore

### The Interactive Dashboard (Recommended)
The best way to explore the findings is through the custom web dashboard.
1. Clone the repository or download `main.html` and `ducati_panigale_v4.png`.
2. Double-click **`main.html`** to open it in your modern web browser (Chrome, Edge, Firefox, Safari).
3. Explore the **Overview**, **Findings**, **Segments**, and the extensive **Interactive Chart Gallery** organized by analysis type.

### The Jupyter Notebooks
If you want to dive into the code and methodology:
1. `Final_Scrapping.ipynb`: View how the raw data was extracted.
2. `Final_Scrapping_EDA.ipynb` & `motorcycle_eda.ipynb`: Follow the data cleaning, feature engineering, and exploratory data analysis steps.
3. `Final_Scrapping_Visualization.ipynb`: See the generation of complex, interactive plots.

---

## 📁 Repository Structure
```text
├── Final_Scrapping.ipynb             # Web scraping logic
├── Final_Scrapping_EDA.ipynb         # Exploratory Data Analysis & Cleaning
├── Final_Scrapping_Visualization.ipynb # Plotly & advanced visualisations
├── motorcycle_eda.ipynb              # Main EDA notebook
├── main.html                         # The Interactive Web Dashboard
├── ducati_panigale_v4.png            # Hero image asset for the dashboard
└── notebook_images/                  # Static image outputs from the notebooks
```
