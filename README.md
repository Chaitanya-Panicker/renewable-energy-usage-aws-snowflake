# 🌱⚡ Renewable Energy Adoption Analysis

<img width="1336" height="774" alt="Screenshot 1" src="https://github.com/user-attachments/assets/ffeee36d-618a-4153-8a73-493791e534a7" />

## 📖 Project Overview  
The world is shifting toward cleaner, renewable energy sources — but adoption patterns vary across regions, income levels, and household types.  
This project tells the story of **how raw renewable energy usage data travels** — from **AWS S3 storage**, through **Snowflake integration**, into **Power BI dashboards** — revealing patterns in adoption, subsidies, and cost savings.  

---

## 🔍 Key Visualizations  
- **Total Household Adoption** — The big picture, in one glance.  
- **Avg Monthly Usage (kWh)** by **Region** — Spot consumption trends.  
- **Income-Level vs Subsidy Received** — Understanding affordability impact.  
- **Energy Source Distribution** — Solar, Wind, Hydro, Biomass, Geothermal.  
- **Adoption Over Time** — Tracking renewable energy uptake year by year.  
- **Geospatial Map** — Country-wise adoption hotspots.  

---

## 💡 Insights & Analysis  
- **Hydro & Solar** dominate energy sources, accounting for over **70%** of adoptions.  
- **Low and Middle-income households** receive most subsidies — critical for increasing adoption.  
- **India leads** adoption rates in the Asia region, with high monthly usage and notable cost savings.  
- **Average household cost savings** stand at **$257/year**, making renewables both sustainable and financially viable.  
- **Adoption spikes** in certain years suggest policy changes or incentive programs at play.  

---

## 🛠 Technologies Used  
- **AWS S3** — Secure cloud storage for the source dataset (`Renewable_Energy_Usage.csv`).  
- **Snowflake** — Cloud data warehouse for data staging, transformation, and querying.  
- **SQL** — Data integration and processing scripts.  
- **Power BI** — Interactive data visualization and storytelling.  

---

## 📂 Project Steps  
1. **Upload Dataset to AWS S3** — Store CSV file in a secure S3 bucket.  
2. **Snowflake Storage Integration** — Use `CREATE STORAGE INTEGRATION` to connect S3 with Snowflake:contentReference[oaicite:0]{index=0}.  
3. **Data Loading & Transformation** — Load CSV into Snowflake tables, apply transformations (e.g., adjusting usage for low-income households).  
4. **Data Analysis in Snowflake** — Query for insights like top regions, energy sources, and subsidy distribution.  
5. **Power BI Visualization** — Connect Snowflake to Power BI, design dashboard, and publish interactive reports.  

---

## 🚀 How to Use  
1. Clone this repository.  
2. Upload your dataset to an AWS S3 bucket.  
3. Set up Snowflake integration using the provided SQL script.  
4. Load and clean your data in Snowflake.  
5. Connect Snowflake to Power BI and apply the provided dashboard template.  

---

## 📬 Contact  
👤 **Chaitanya Panicker**  
📧 chaitanya.panicker98@gmail.com  
🌐 https://www.linkedin.com/in/chaitanyapanicker  

---

## 📜 License  
This project is licensed under the **MIT License** — free to use, modify, and share with attribution. 
