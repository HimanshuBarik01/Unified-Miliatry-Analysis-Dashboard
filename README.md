# Unified Military Analytics and Comparison Dashboard

## 📌 Project Overview

The **Unified Military Analytics and Comparison Dashboard** is an interactive analytics project designed to analyze and compare the military capabilities of **140+ countries** using 2025 global military data.

The project uses Python-based data pipelines to collect, clean, process, and transform open-source military data from **GlobalFirepower.com**. The processed dataset is then used to create interactive dashboards for exploring military strength, country-level capabilities, comparisons, and coalition-level analysis.

The project combines **50+ military, defense, and economic indicators** into a unified analytics platform.

---

## 🎯 Objectives

The main objectives of this project are:

* Collect military data for 140+ countries
* Automate the data collection process using Python
* Clean and standardize raw military data
* Handle missing and inconsistent values
* Generate meaningful military KPIs
* Build interactive dashboards
* Compare military capabilities between countries
* Analyze individual country profiles
* Simulate combined military strength through coalition analysis
* Provide an intuitive and interconnected dashboard experience

---

## 📊 Data Source

Military data is collected from:

**GlobalFirepower.com**

The scraping process uses a predefined list of country URLs stored in:

```text
links_for_military_data.txt
```

The project collects country-level military metrics such as aircraft, tanks, military personnel, defense budget, naval assets, and other indicators.

---

## 🔄 Project Workflow

```text
GlobalFirepower.com
        ↓
URL List
        ↓
Python Web Scraping
        ↓
Raw Military Dataset
        ↓
Data Cleaning & Processing
        ↓
KPI Feature Engineering
        ↓
Final Dataset
        ↓
Interactive Dashboards
        ↓
Military Analysis & Comparison
```

---

# 🧩 Dashboard Modules

The project consists of four interconnected dashboard modules.

## 1. 🌍 Quick Stats

Provides a global overview of military power.

### Features

* Top 10 countries by Power Index
* Global military statistics
* Dynamic KPI cards
* Region filters
* Continent filters
* Alliance filters
* Interactive visualizations

The Quick Stats dashboard provides a high-level view of global military rankings and important military indicators.

---

## 2. 🏳️ Nation Overview

Provides a detailed profile of an individual country.

### Features

* Country selection
* Military capability overview
* Military personnel analysis
* Aircraft and land-force analysis
* Naval capability analysis
* Defense budget information
* Ranking and comparison information
* Interactive charts
* Tooltips for additional information

Users can select a country and explore its major military metrics through interactive visualizations.

---

## 3. ⚔️ Compare Powers

Allows users to compare the military capabilities of two countries side by side.

### Comparison Metrics

* Manpower
* Aircraft
* Navy
* Defense Budget
* Power Index
* Other calculated KPIs

The dashboard allows users to select two countries and directly compare their military capabilities.

---

## 4. 🤝 Coalition Builder

The Coalition Builder allows users to simulate the combined military strength of multiple countries.

### Features

* Multi-country selection
* Combined military statistics
* Aggregated coalition metrics
* Coalition comparison
* Comparison against another coalition or reference country

This module provides an interactive way to understand how military assets change when multiple countries are considered together.

---

# 📈 Key Performance Indicators

The project derives additional KPIs from the collected military and economic data.

### Power Index Rank Gap

Measures the difference between relevant Power Index rankings.

### Assets per Capita

Measures military assets relative to the population of a country.

### Defense Budget-to-GDP Ratio

Measures defense expenditure relative to the country's GDP.

Additional metadata such as **region, continent, and alliance information** is also incorporated into the dataset.

---

# 🧹 Data Processing

The raw scraped data is cleaned and standardized before being used for analysis.

### Cleaning Operations

* Remove commas and unnecessary symbols
* Remove percentage symbols
* Convert text-based metrics into numeric values
* Standardize column names
* Handle missing and null values
* Structure data for dashboard visualization

The project targets a cleaned dataset with less than **2% missing/null data** after processing.

---

# 🛠️ Technology Stack

| Category        | Technologies                          |
| --------------- | ------------------------------------- |
| Programming     | Python                                |
| Web Scraping    | Requests, BeautifulSoup               |
| Data Processing | Pandas, NumPy                         |
| Visualization   | Power BI / Tableau / Streamlit / Dash |
| Data Format     | CSV, Excel                            |
| Version Control | Git, GitHub                           |
| Documentation   | Markdown                              |

The project specification lists Python, Requests, BeautifulSoup, Pandas, NumPy, Tableau, Streamlit, Power BI and Dash among the technologies used across the project workflow.

---

# 📂 Project Structure

```text
Unified-Military-Analytics/
│
├── dataset/
│   ├── military_data.csv
│   ├── aircraft_data.csv
│   └── ...
│
├── scripts/
│   ├── scraping scripts
│   ├── data cleaning scripts
│   └── KPI generation scripts
│
├── dashboard/
│   └── military_dashboard.pbix
│
├── docs/
│   ├── storyboard
│   └── dashboard documentation
│
├── links_for_military_data.txt
│
├── README.md
│
└── requirements.txt
```

---

# 🔧 Data Pipeline

## Step 1 — Data Collection

Python scripts collect military information from the predefined GlobalFirepower country URLs.

## Step 2 — Data Cleaning

Raw data is processed using Pandas and converted into a structured dataset.

## Step 3 — KPI Generation

Additional analytical KPIs are calculated from military, population, and economic data.

## Step 4 — Dashboard Development

The processed data is imported into the visualization platform and transformed into interactive dashboards.

## Step 5 — Dashboard Integration

Navigation buttons, filters, slicers, and interactions are used to connect the four dashboard modules.

## Step 6 — Testing

The dashboards are tested for:

* Filter functionality
* Navigation
* Data accuracy
* KPI calculations
* Visual consistency
* User interaction

---

# 🔗 Dashboard Navigation

The four dashboards are interconnected to provide a seamless user experience.

```text
                Quick Stats
                    ↓
        ┌───────────┼───────────┐
        ↓           ↓           ↓
 Nation Overview  Compare Powers  Coalition Builder
        ↓           ↓           ↓
        └───────────┴───────────┘
              Interactive Analysis
```

Navigation controls allow users to move between the different analytical modules while maintaining an integrated dashboard experience.

---

# 📊 Expected Outcomes

The project delivers:

* Military dataset covering 140+ countries
* 50+ military and economic indicators
* Automated Python-based data collection
* Cleaned and standardized datasets
* Custom military KPIs
* Four interactive dashboard modules
* Cross-dashboard navigation
* Interactive filters and selectors
* Country comparison functionality
* Coalition analysis functionality
* GitHub-hosted project documentation

---

# 🧪 Testing & Quality Assurance

The project includes testing of:

* Dashboard filters
* Country selection
* Navigation buttons
* KPI calculations
* Data accuracy
* Tooltips
* Dashboard layouts
* Cross-dashboard interactions

The final dashboard should provide smooth navigation and accurate data visualization without functional issues.

---

# 🚀 Future Scope

The project can be further extended by:

* Adding more military indicators
* Adding historical year comparisons
* Adding additional countries and datasets
* Implementing advanced predictive analytics
* Publishing the dashboard online
* Adding automated data-refresh pipelines
* Integrating additional defense and economic data sources

---

# 👨‍💻 Author

**Himanshu Barik**

B.Tech — Computer Science & Engineering

---

## ⭐ Project Highlights

> **140+ Countries • 50+ Indicators • 4 Interactive Dashboards • Python Data Pipeline • Military Analytics**

This project demonstrates the use of **web scraping, data cleaning, feature engineering, KPI development, data visualization, and interactive dashboard design** to create a unified military analytics platform.
