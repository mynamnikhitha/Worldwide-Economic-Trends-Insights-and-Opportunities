# Worldwide-Economic-Trends-Insights-and-Opportunities

This project explores key global economic indicators using data from the **World Bank** to uncover insights that help understand development patterns and disparities across regions. By leveraging Python and Tableau, performed a full-cycle data analysis — from data cleaning and exploration to visual storytelling and conclusions.

---
Project Structure
- Source Data: World Bank Open Data via Kaggle ([Dataset Link](https://www.kaggle.com/datasets/yusufglcan/country-data/data))
- Tools Used: Python (Pandas, NumPy, Matplotlib, GeoPandas), Tableau
- Data Size: 5,105 records across 25 economic and demographic indicators
- Years Covered: 2000–2022
- Countries: ~100 countries from all continents
---
 Project Objectives
- Analyze and visualize trends in GDP, education, healthcare, trade, and population.
- Understand how investments in human capital (education & health) relate to economic growth.
- Explore regional disparities and their policy implications.
- Segment global economies for clearer comparative insights.

---

## Methodology

1. Data Preparation
- Removed duplicates
- Filtered for relevant years (2000–2022)
- Handled missing values across multiple economic indicators

2. Analysis and Visualizations

| Visualization | Description |
|---------------|-------------|
| **Scatter Plot** | GDP Per Capita vs. Education Expenditure (% GDP) by continent |
| **Line Charts** | GDP growth & population trends across continents (2000–2022) |
| **Bar Charts** | Average health expenditure (% GDP) by continent |
| **Map** | Choropleth map of GDP Per Capita by country using GeoPandas |
| **Dual Bar Chart** | Education vs. Health Expenditure by continent in 2022 |

---

## Key Insights

- Strong correlation between GDP per capita and both education & healthcare investment.
- Significant disparities between Global North and Global South in economic development.
- Population growth is steeper in developing regions, demanding more investment.
- Developed regions invest more consistently in healthcare (up to 5x more).
- Trade alone doesn’t explain GDP variance — human capital matters more.

---
## Recommendations

- Prioritize education and health spending for sustainable long-term growth.
- Implement inclusive trade and infrastructure policies to reduce regional disparities.
- Strengthen global cooperation to address shared challenges and foster equitable development.

---

## Files Included
- pdf: Full analysis notebook with code and plots
- Worldwide-Economic-Trends-Insights-and-Opportunities.pptx: Final project presentation deck
- Tableau file: Tableau workbook with dynamic dashboards

---

## Future Work

- Add time series forecasting on GDP and population
- Incorporate more granular indicators (e.g., internet penetration, renewable energy)
- Build an interactive dashboard using Plotly or Streamlit
