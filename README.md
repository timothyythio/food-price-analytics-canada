# Food Price Analytics (Canada)

SQL and BI analysis of Canadian food prices, examining regional and product-level price trends.

---

## 📌 Project Overview

Food plays a fundamental role in everyday life. As a basic physiological need alongside water and shelter, access to affordable food is essential to both individual well-being and broader social stability. In recent years, however, food and grocery prices in Canada have risen steadily, influenced by factors such as supply chain disruptions, climate change, and rising labor costs. While inflation affects food broadly, price increases have not been uniform across products, prompting closer examination of how economic pressures and demand patterns shape food affordability.

This project focuses on **product-level price behavior** within the Canadian protein market, using public data to explore whether certain foods experience price changes that differ meaningfully from staple proteins. Rather than attempting to predict prices or attribute causation, the goal is to **describe, compare, and visualize price trends** in a clear and transparent way.

---

## 🎯 Research Question

**Do demand-sensitive beef cuts, such as short ribs, exhibit price behavior that diverges from staple proteins like chicken breast and ground beef, and how does this divergence manifest in British Columbia relative to Alberta and broader Canadian trends?**

---

## 🧭 Scope & Focus

### Geographic Scope
- **Primary region:** British Columbia (consumption-oriented market)
- **Secondary region:** Alberta (production-oriented market)
- **Reference:** Canada-wide trends (contextual benchmark)

### Product Scope
- **Chicken breast** – industrially efficient, mass-consumed staple protein  
- **Ground beef** – baseline beef product reflecting broader cattle and processing costs  
- **Beef short ribs** – demand-sensitive beef cut, examined contextually  

---

## 🧠 Key Concepts

### Price Divergence
Price divergence refers to differences in how prices evolve over time, including disparities in growth rates and price stability across products and regions.

### Demand-Sensitive Products
Products whose pricing may be influenced not only by production costs and inflation, but also by shifts in consumer preferences, cultural trends, or downstream demand.

---

## 📊 Analytical Approach

This project uses **descriptive and comparative analytics**, rather than predictive modeling.

### Core Metrics
- **Relative price growth**
  - Prices converted to indexed series (base period = 100)
  - Enables comparison of long-term growth trends across products
- **Price volatility**
  - Month-to-month percentage change
  - Rolling standard deviation to assess stability over time

### What This Project Does Not Do
- Does not model causal relationships  
- Does not predict future prices  
- Does not evaluate policy effectiveness  

The analysis is intentionally restrained to observable price behavior.

---

## 🗂️ Data Sources

All data used in this project is **publicly available and aggregated**.

- **Statistics Canada**
  - Consumer Price Index (CPI)
  - Average Retail Prices of Food
- Monthly frequency
- Provincial and national coverage

---

## 🛠️ Tools & Workflow

### Primary Tools
- **SQL** – data modeling, transformations, and analytical queries
- **Tableau / Power BI** – visualization and dashboard development

### Supporting Tools
- **Excel** – exploratory inspection and validation

### Workflow
1. Raw data ingestion  
2. SQL-based transformations and metric calculation  
3. BI dashboard development  
4. Written insight summary  

---

## 📈 Expected Outputs

- SQL tables and/or views prepared for analysis
- Interactive BI dashboard(s)
- Written summary of findings and limitations

---

## ✅ Success Criteria

This project is considered successful if it:
- Clearly demonstrates whether product-level price divergence exists
- Shows how price behavior differs across regions
- Communicates insights through SQL-backed dashboards
- Maintains transparency in methodology and limitations

---

## 📎 Notes

This project is intended as an **applied analytics case study**.  
It prioritizes clarity, methodological discipline, and real-world relevance over technical complexity.

