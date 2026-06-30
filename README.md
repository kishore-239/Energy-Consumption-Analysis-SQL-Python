# Energy-Consumption-Analysis-SQL-Python

# 🌍 Energy Consumption Analysis using MySQL & Python

---

## 💡 Introduction
This project focuses on analyzing **global energy consumption, production, and emissions** using **real-world datasets** from the EIA (Energy Information Administration).  
It explores how **economic growth**, **population**, and **energy use** are interlinked across different countries.  
Using **MySQL** for data analysis and **Python** for visualization, meaningful insights into energy efficiency, emission trends, and sustainability were uncovered.

---

## 🧩 Problem Statement
The rapid rise in global energy consumption has created serious **environmental and economic challenges**.  
Different countries vary widely in their energy production and usage patterns, resulting in disparities in **emissions**, **efficiency**, and **sustainability**.

This project aims to:
- Analyze and compare global **energy production**, **consumption**, **GDP**, and **emissions** data.  
- Identify **key contributors** to global emissions.  
- Evaluate **energy efficiency** through per-capita and GDP-based ratios.  
- Provide insights to support **sustainable energy policies** and planning.

---

## 🗄️ Database Design

The database was created in **MySQL** under the schema name `energydb9` with the following six related tables:

| Table Name | Description |
|-------------|--------------|
| `country_3` | Master table containing country names and unique IDs |
| `emission_3` | Annual CO₂ emissions by country and energy type |
| `consum_3` | Energy consumption by country and year |
| `production_3` | Energy production by country and year |
| `gdp_3` | GDP data by country and year |
| `population_3` | Population data by country and year |

All tables are linked via **foreign keys** referencing the `country_3` table.

---

## 📊 Key Analyses (18 Major Queries)
The project answers 18 analytical questions categorized into four sections:

### **1️⃣ General & Comparative Analysis**
- Total emissions per country  
- Top 5 countries by GDP  
- Energy production vs consumption comparison  
- Top energy types contributing to global emissions  

### **2️⃣ Trend Analysis Over Time**
- Global emissions change year-over-year  
- GDP and population growth trends  
- Impact of population growth on emissions  
- Energy consumption changes in major economies  

### **3️⃣ Ratio & Per Capita Analysis**
- Emission-to-GDP ratio  
- Energy consumption per capita  
- Energy production per capita  
- Correlation between GDP growth and production growth  

### **4️⃣ Global Comparisons**
- Top 10 countries by population vs emissions  
- Countries reducing per capita emissions  
- Global share (%) of emissions by country  
- Global averages of GDP, emissions, and population  

---

## ⚙️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **MySQL** | Database design, SQL queries, data management |
| **Python (Jupyter Notebook)** | Data visualization & analysis |
| **Pandas, Matplotlib, Seaborn** | Visualization & data wrangling |
| **PowerPoint** | Presentation of insights and conclusions |

---

## 🗂️ Repository Contents

| Folder/File | Description |
|--------------|-------------|
| `*.csv` | Source datasets (6 tables) |
| `energy_consumption_9.sql` | Contains all 18 SQL queries |
| `mysql_visualisations.ipynb` | Python visualization notebook |
| `sample_ppt_energy_final.pptx` | Final presentation slides |
| `README.md` | Project documentation |

---

## 📈 Visual Insights
Some of the key visualizations created using Python:
- 📊 **Production vs Consumption** — Balance of energy use across nations  
- 🌡️ **Global Emission Trends** — Change in emissions over time  
- 💰 **Top GDP Economies** — Relation between economic size and energy demand  
- 👥 **Population vs Emissions** — How population size affects environmental impact  

---

## 🧭 Key Findings
- A small number of countries are responsible for the majority of global emissions.  
- **Coal and petroleum** remain dominant emission sources.  
- High GDP often correlates with higher energy consumption.  
- Several countries show improvement in **per-capita emission reduction**.  
- Population growth continues to drive total emissions upward.  

---

## 💬 Conclusion
> **Energy, economy, and environment are deeply connected**, influencing one another in every watt consumed and every emission released.  
>  
> By harnessing **MySQL** and **Python**, raw energy data was transformed into powerful insights — identifying global patterns in production, consumption, and sustainability.  
>  
> This project highlights that **sustainable growth is not just a choice — it's a necessity**. The future belongs to those who can transform **data into action** and **energy into opportunity** for a cleaner planet. 🌱

---

## 🏷️ Keywords
`SQL` `Python` `MySQL` `Data Analysis` `Energy Analytics` `Visualization` `Sustainability` `Matplotlib` `Seaborn` `Pandas`

---

## 📫 Connect
📧 Email: [kishorekrishna623@gmail.com](mailto:kishorekrishna623@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/krishnakishorekudithi/)  
🐙 [GitHub](https://github.com/kishore-239)
