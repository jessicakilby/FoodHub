# 📊 Food Hub
        
## Project Overview

This project explores order data from a food aggregator platform, where registered customers place orders through an online portal. The company aims to analyze this data to better understand restaurant demand patterns and enhance the overall customer experience.

As a newly hired Data Scientist, I am tasked with investigating key business questions provided by the Data Science team. My analysis will uncover actionable insights to support strategic decisions and improve operational efficiency.

The dataset includes order-level details, and my work focuses on identifying trends, evaluating restaurant performance, and recommending data-driven improvements to optimize the platform’s offerings.
        
## Folder Structure
- `data/`: Raw and cleaned datasets
- `notebooks/`: ETL, reporting logic, exploratory analysis and visualizations
- `venv/`: Virtual environment
        
## Setup Instructions
1. Clone the repo or copy the folder
2. Create and activate the virtual environment:
    python -m venv venv venv\Scripts\activate
3. Install dependencies:
    pip install -r requirements.txt
        
## Key Scripts
- `FoodHub.ipynb`: This Jupyter Notebook contains the full workflow for the project, including data import, cleaning, exploration, and analysis. It addresses core business questions using Python libraries such as pandas, matplotlib, and seaborn, and presents insights to support strategic decisions around restaurant demand and customer experience.

> **Disclaimer**: The Markdown content and analytical workflow within the notebook were provided by Great Learning as part of their instructional material. This includes the structure, prompts, and guiding questions for the analysis. All Python code cells, data cleaning, and exploratory work were authored independently.
        
        
## Notes
- Data source: foodhub_order (CSV)
- Contact: Jessica Kilby


## Progress Log

**2025-09-22**  
Completed Section 1 (Questions 1–5) of the analysis.  
- Explored key features including `restaurant_name`, `cuisine_type`, `cost_of_the_order`, `day_of_the_week`, `rating`, and `delivery_time`.
- Identified missing values and non-standard entries such as `'Not given'` in the `rating` column.
- Generated descriptive statistics and observations to support future imputation and modeling.
- Documented insights in Markdown cells for clarity and stakeholder readability.

**2025-09-23**
Completed Section 2 (Questions 6–11) of the analysis.
- Performed univariate analysis on cost_of_the_order and delivery_time, including summary statistics and visualizations.
- Calculated the percentage of orders exceeding $20 and visualized the result using a pie chart.
- Determined the mean delivery time and formatted it for professional reporting.
- Identified the top five customers by order count and extracted their IDs for further analysis.
- Composed stakeholder-ready insights and refined phrasing for observations and README documentation.
- Identified the most popular cuisine type on weekends using a countplot, highlighting customer preferences by day.

**2025-09-24**
- Implemented tiered commission logic for company revenue.
- Filtered restaurants by rating count (>50) and average rating (>4.0).
- Generated insights and visualizations for top-performing restaurants.
- Explored weekend cuisine trends and refined summary phrasing.
- Validated and documented net revenue calculations.

**2025-09-25**
- Refined visual observations across all dashboard plots, clarifying weekday vs weekend trends and correcting phrasing for accuracy.
- Cleaned up markdown formatting in the README, including escaped dollar signs. Added missing comments to code cells.
- Enhanced the correlation heatmap by renaming columns for clarity and removing irrelevant identifiers (customer_id, order_id).
