# Data Analytics Project: End-to-End Business Performance Analysis

## Overview
This repository contains an end-to-end data analytics project designed to extract, clean, analyze, and visualize business performance data. The workflow spans from initial Python-based Exploratory Data Analysis (EDA) and data cleansing, through robust database querying, up to executive-ready reporting and interactive dashboarding. The goal is to transform raw transactional data into actionable operational insights.

## Dataset
*   **Source:** [Specify your dataset source here, e.g., Kaggle / Company Internal Data]
*   **Size:** [Specify size, e.g., 50,000+ rows, 15 columns]
*   **Description:** The dataset comprises transactional records including Customer IDs, Product Categories, Sales, Profit Margins, Order Dates, and Regional Metrics. 

## Tools & Technologies
*   **Data Processing & EDA:** Python (Pandas, NumPy, Matplotlib, Seaborn)
*   **Database Management:** PostgreSQL / MySQL / SQL Server (Choose your dialect)
*   **Visualization & BI:** Power BI
*   **Reporting:** Markdown / PDF Report
*   **Presentations:** Gamma AI (AI-powered slide generation)

## Project Steps

### 1. Data Cleaning & EDA (Python)
*   Handled missing values, duplicates, and out-of-bound anomalies.
*   Standardized date formats and categorical text data.
*   Performed distribution analysis and correlation mapping using Seaborn.
*   *Artifact:* `notebooks/eda_and_cleaning.ipynb`

### 2. Database Integration & Querying (SQL)
*   Imported the structured dataset into a relational database.
*   Wrote optimized SQL queries to extract key business performance metrics:
    *   Year-over-Year (YoY) growth rates.
    *   Top 10 highest-performing products by profit margin.
    *   Customer segmentation based on purchase frequency.
*   *Artifact:* `sql/analytical_queries.sql`

### 3. Interactive Dashboard (Power BI)
*   Developed a dynamic, multi-page Power BI dashboard.
*   Modeled data relationships (Star Schema) and built calculated measures using DAX.
*   *Key Features:* Dynamic date filters, KPI cards, regional performance maps, and trend lines.
*   *Artifact:* `dashboards/business_performance.pbix`

### 4. Executive Reporting & Presentation
*   Compiled detailed analytical findings into a structured PDF/Markdown report.
*   Leveraged Gamma AI to rapidly generate a visually compelling PowerPoint deck tailored for stakeholders.

## Dashboard Visuals & Results
*   **Financial Impact:** Identified an underperforming product category, leading to a strategic recommendation that recovers ~5% in lost margin.
*   **Efficiency:** Replaced manual Excel-based weekly reporting with an automated Power BI pipeline.
*   *(Optional)* Place a screenshot of your Power BI dashboard here: `images/dashboard_screenshot.png`

## How to Run
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/data-analytics-project.git
    ```
2.  **Environment Setup:** Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the EDA Notebook:** Open and execute `notebooks/eda_and_cleaning.ipynb` to inspect the preprocessing steps.
4.  **Database Setup:** Execute the schema script in `sql/schema.sql` and run the queries in `sql/analytical_queries.sql`.
5.  **View Dashboard:** Open `dashboards/business_performance.pbix` using Power BI Desktop.
