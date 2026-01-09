# Canada-quality-of-life-Power-BI-dashboard
## Overview

This project presents an interactive **Power BI dashboard** built using **Statistics Canada** data to analyze and visualize Canada’s **Quality of Life (QoL) Framework**. The dashboard provides a comprehensive, data-driven view of national well-being by integrating indicators across **Society, Prosperity, Health, Governance, and Environment**.

The goal of this project is to transform complex public datasets into clear, actionable insights that support policy analysis, academic research, and public understanding of how quality of life in Canada has evolved from **2021 to 2024**.

---

## Key Objectives

* Consolidate multiple Statistics Canada datasets into a unified analytical model
* Apply robust data cleaning, transformation, and modeling techniques in Power BI
* Develop interactive dashboards aligned with Canada’s Quality of Life Framework
* Enable trend analysis, year-over-year comparison, and geographic exploration

---

## Data Sources

All data used in this project is sourced from **Statistics Canada**, primarily through:

* Canada’s **Quality of Life (QoL) Hub**
* Official Statistics Canada data tables (CSV format)

Datasets cover national and provincial-level indicators and are aligned with official QoL definitions to ensure consistency and reliability.

---

## Dashboard Structure

### 1. Society

Focuses on social cohesion and connectedness using four headline indicators:

* Sense of belonging to local community
* Having someone to count on
* Trust in others
* Satisfaction with time use

Includes KPI cards, trend analysis, gender comparisons, and a composite Society score.

---

### 2. Prosperity

Examines economic well-being and financial security through:

* Labour force characteristics
* Market income and government transfers
* Low-income indicators

Visuals highlight long-term trends, provincial disparities, and year-over-year changes.

---

### 3. Health

Analyzes physical and mental well-being using four key indicators:

* Perceived health (very good or excellent)
* Perceived mental health (very good or excellent)
* High blood pressure
* Diabetes

Includes trend analysis, provincial comparisons, and age-group breakdowns.

---

### 4. Governance

Evaluates trust and institutional effectiveness through:

* Confidence in institutions
* Trust in media
* Cyberbullying
* Discrimination and unfair treatment

Features normalized scores, moving averages, and a composite governance index.

---

### 5. Environment

Assesses environmental sustainability using:

* Air Quality (PM2.5 exposure)
* Greenhouse Gas (GHG) emissions

Visuals include trend lines, year-over-year change indicators, and sector-level breakdowns for emissions.

---

### 6. Summary Dashboard

A unified executive-level overview combining all domains:

* Cross-domain trends
* Composite indicators
* Shared Year and Geography slicers
* Fully synchronized interactions across all pages

---

## Data Modeling & Analytics

* Star-schema data model with shared **Date** and **Geography** dimensions
* Standardized indicator structures across all domains
* Advanced **DAX measures** including:

  * Latest Value
  * Previous Year Value
  * Year-over-Year Change (%)
  * Moving Averages
  * Normalized Scores (0–100)
  * Composite Headline Indices

---

## Tools & Technologies

* **Power BI Desktop**
* **Power Query** (data cleaning & transformation)
* **DAX** (advanced analytics)
* **Statistics Canada Open Data**
* **Power BI Service** (dashboard publishing)

---

## Key Insights

* Social well-being indicators show recent improvement, particularly in community belonging and time-use satisfaction
* Long-term income growth contrasts with persistent low-income vulnerability in certain regions
* Perceived mental health lags behind physical health nationally
* Environmental indicators show mixed progress, with sector-level variation in GHG emissions
* Trust-based governance indicators fluctuate over time, reflecting broader social conditions

---

## Future Enhancements

* Additional demographic segmentation (education, ethnicity, income groups)
* Predictive analytics for long-term QoL forecasting
* Automated data refresh via Statistics Canada APIs
* Expanded environmental and climate indicators

---

## References

* Statistics Canada – Quality of Life Hub
* Statistics Canada Data Tables (QoL indicators)
* Microsoft Power BI Documentation

---

## Dashboard Access

The completed report has been published to **Power BI Service**, allowing interactive exploration through a web browser without requiring Power BI Desktop.

---

## License

This project is for **educational and analytical purposes**. All data remains the property of Statistics Canada and is used in accordance with open data guidelines.
