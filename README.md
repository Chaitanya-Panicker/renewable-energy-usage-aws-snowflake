# 🌱⚡ Renewable Energy Adoption Analysis  

**Domain:** Renewable Energy & Sustainability Analytics | **Type:** Cloud Data Pipeline + BI Dashboard  

---

## 🎯 Project Overview  
An **end-to-end cloud-powered analytics solution** that tracks and analyzes **renewable energy adoption patterns** across regions and demographics.  
Built using **AWS S3**, **Snowflake**, and **Power BI**, this pipeline processes household energy usage data from **S3 bucket `powerbiproject01`** and delivers **interactive insights** into cost savings, energy source preferences, and subsidy distribution.  

---

## 📊 Key Visualizations  

- **Core Metrics:**  
  - 15 Total Household Adoption  
  - 912.38 kWh Avg Monthly Usage  
  - $257.03 Avg Cost Saving  
  - 40% Subsidy Received Households  
- **Regional Usage:** Horizontal bar chart – *Asia leads with 1000 kWh monthly usage*  
- **Subsidy Distribution:** Income-level breakdown – Low (6), Middle (3), High (2)  
- **Energy Source Pie Chart:** Wind (46.67%), Solar (26.67%), Geothermal (20%), Biomass (6.67%)  
- **Adoption Timeline:** Peaks at 2015 & 2020 (3 households each)  
- **Geographic Map:** Household concentration with India highlighted  
- **Interactive Filters:** Country, Income Level, Urban/Rural  

---

## 🔍 Insights & Analysis  

- **Wind Energy Dominance** – Nearly half (46.67%) of households prefer wind power  
- **Regional Leadership** – Asia has the highest average consumption at 1000 kWh  
- **Equity in Subsidies** – Low-income households receive most subsidies (6 of 11 total)  
- **Adoption Waves** – Peaks in 2015 & 2020 hint at policy/economic triggers  
- **Urban Preference** – Higher adoption rates in urban areas  
- **Financial Incentives** – $257.03 average savings motivates adoption  

---

## 🛠️ Technologies Used  

- **AWS S3** – Data storage (`Renewable_Energy_Usage.csv`, 70.5 KB)  
- **Snowflake** – External stage integration with IAM role security  
- **Database** – `powerbi_Data` schema with household-level metrics  
- **Power BI** – Interactive dashboard & filters  
- **ETL Pipeline** – COPY INTO commands, CSV parsing, data transformations  

---

## 🚀 Project Steps  

1. **S3 Setup** – Created bucket & uploaded CSV dataset  
2. **Snowflake Integration** – Storage integration `powerbi_s3` with IAM role  
3. **Database Creation** – Structured schema & tables  
4. **Data Loading** – COPY INTO from S3 stage with error handling  
5. **Data Processing** – Applied transformations (e.g., +10% usage for low-income)  
6. **Dashboard Development** – Visuals, filters, and map integration  

---

## 📌 How to Use  

- **Data Refresh:** Upload new CSV to S3 → Run Snowflake COPY commands  
- **Filter View:** Country, Income Level, Urban/Rural toggles in dashboard  
- **Regional Insights:** Click regions in bar chart for detailed metrics  
- **Energy Mix:** Use pie chart to isolate sources  
- **Trend Analysis:** Check timeline chart for policy/seasonal impacts  
- **Geo Drilldown:** Map clicks reveal country-specific stats  

---

## 📬 Contact  

📧 **Email:** your-email@example.com  
💼 **LinkedIn:** [Your LinkedIn Profile]  
🐙 **GitHub:** [Your GitHub Profile]  

---

## 📄 License  

This project is licensed under the **MIT License** – see the LICENSE file for details.  
