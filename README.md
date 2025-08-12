# 🌱⚡ Renewable Energy Adoption Analysis

## Project Overview
Complete cloud data pipeline analyzing renewable energy adoption patterns using AWS S3, Snowflake, and Power BI. The project processes household energy usage data stored in S3 bucket 'powerbiproject01' with 70.5 KB CSV file, integrated through Snowflake external stage for comprehensive renewable energy insights across regions and demographics.

## Key Visualizations
- **Core Metrics**: 15 Total Household Adoption, 912.38 Avg Monthly Usage (kWh), $257.03 Avg Cost Saving, 40% Subsidy Received Households
- **Regional Usage**: Asia region showing 1000 kWh average monthly usage in horizontal bar chart
- **Subsidy Distribution**: Income level breakdown with Low (6 count), Middle (3 count), High (2 count) subsidies received
- **Energy Source Pie Chart**: Wind 46.67%, Geothermal 20%, Solar 26.67%, Biomass 6.67% household distribution
- **Adoption Timeline**: Line graph from 2010-2020 showing peaks at 2015 (3 households) and 2020 (3 households)
- **Geographic Map**: Country distribution with India highlighted, showing household concentration
- **Interactive Filters**: Country (India selected), Income Level (All), Urban_Rural (Urban selected)

## Key Insights & Analysis
- **Wind Energy Dominance**: 46.67% of households adopt wind energy, making it the leading renewable source
- **Regional Leadership**: Asia demonstrates highest consumption at 1000 kWh monthly usage
- **Subsidy Pattern**: Low-income households receive most subsidies (6 out of 11 total), promoting energy equity
- **Adoption Waves**: Clear peaks in 2015 and 2020 indicating policy-driven or economic catalyst periods
- **Geographic Focus**: India represents primary market with concentrated household adoption
- **Urban Preference**: Urban areas show higher renewable energy adoption rates
- **Cost Benefits**: $257.03 average savings demonstrates strong financial incentive for adoption

## Technologies Used
- **AWS S3**: Storage bucket 'powerbiproject01' with 'Renewable_Energy_Usage.csv' (70.5 KB, Standard storage class)
- **Snowflake**: External stage integration with IAM role 'arn:aws:iam::518503251154:role/powerbirole'
- **Database**: Schema with Household_ID, Region, Country, Energy_Source, Monthly_Usage_kWh, Income_Level fields
- **Power BI**: Interactive dashboard with country, income level, and urban/rural filtering capabilities
- **ETL Pipeline**: Snowflake COPY INTO commands with CSV field delimiter and header skip functionality

## Project Steps
1. **S3 Setup**: Created bucket 'powerbiproject01' and uploaded renewable energy CSV dataset (last modified July 8, 2025)
2. **Snowflake Integration**: Established storage integration 'powerbi_s3' with AWS role-based security
3. **Database Creation**: Built 'powerbi' database with 'powerbi_Data' schema and structured table definitions
4. **Data Loading**: Implemented COPY INTO operation from S3 stage with error handling ('continue' on error)
5. **Data Processing**: Applied transformations including 10% usage increase for low-income households
6. **Dashboard Development**: Created Power BI visualizations with geographic mapping and interactive filtering

## How to Use
1. **Data Pipeline**: Upload new CSV files to S3 bucket and execute Snowflake COPY commands for data refresh
2. **Dashboard Filters**: Select specific countries, adjust income levels (All/Low/Middle/High), toggle Urban/Rural settings
3. **Regional Analysis**: Click on Asia or other regions in bar chart to view detailed consumption patterns  
4. **Energy Source Analysis**: Interact with pie chart segments to isolate specific renewable energy types
5. **Trend Analysis**: Use adoption year line chart to identify seasonal or cyclical patterns
6. **Geographic Exploration**: Click on map regions to drill down into country-specific adoption metrics

## Contact
📧 Email: [your-email@example.com]
💼 LinkedIn: [Your LinkedIn Profile]
🐙 GitHub: [Your GitHub Profile]

## License
This project is licensed under the MIT License - see the LICENSE file for details.
