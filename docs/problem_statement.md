# Live API Data Integration: Real-Time Dashboards with Python & Power BI

This project focuses on building a live, interactive dashboard that shows important global statistics such as health, education, employment, and other key indicators. The data comes from a public API that is regularly updated with the latest information. Using Python, we write a script that automatically fetches this data from the API and processes it for analysis. This ensures that the data is fresh and accurate without manual downloads or updates.

The Python script is then connected directly to Power BI, creating a live data connection. Because of this live integration, the Power BI dashboard refreshes automatically whenever new data is available. Users do not need to perform any manual steps to update the dashboard, making it highly efficient and reliable for ongoing monitoring. The dashboard provides easy-to-understand visuals like charts and graphs, which help users explore trends and patterns across different countries and regions.

Once the connection is created, we will create a dashboard that will address the following questions:

### 1. Understand the overall economic and social landscape

To get a clear baseline of the countries we are analyzing to understand key average economic and development metrics. Specifically, we want to know:

1. What is the average GDP per capita, giving us a sense of individual economic well-being?
2. What is the average trade value, showing how active countries are in international markets?
3. How much on an average spending on health relative to their GDP, which indicates national health investment priorities?
4. What is the average GDP growth rate, revealing overall economic momentum?
5. What proportion of the total area of countries is classified as forest, which affects land use, agriculture, and natural resource policies.
6. These metrics provide foundational context before diving into deeper analyses.

### 2. Compare health spending patterns across regions

Compare average health spending (as a % of GDP) across different world regions to see which regions invest more or less in health. This will help highlight regional disparities and may point to broader differences in health outcomes or priorities.

### 3. Analyze trends in key socio-economic indicators over time

How critical indicators — such as forest area, mobile subscriptions, internet subscriptions, GDP, renewable energy use, and unemployment — have changed over time. These trend insights will inform whether countries are moving in positive or negative directions in their development pathways.

### 4. Evaluate the impact of internet access on immunization awareness

Analyzing particularly in raising awareness about immunization. We want to assess if there's a relationship between higher internet penetration and higher immunization rates, suggesting that digital connectivity may be improving health information access and public engagement.

### 5. Assess the role of internet access in reducing unemployment

Another important area is the potential economic impact of the internet. Specifically, has expanding internet penetration helped to reduce unemployment levels?

### 6. Identify underperforming countries in poverty reduction efforts

To identify where development interventions are most urgently needed, we need to pinpoint the bottom 10 countries that have shown the least progress in reducing poverty over time. This will allow policymakers, NGOs, and donors to focus resources and strategies on the countries struggling the most.

### 7. Identify top-performing countries in poverty reduction efforts

On the flip side, we also want to learn from success stories. Which are the top 10 countries that have made the most progress in reducing poverty over the years? Understanding the characteristics and policies of these high-performing countries can provide valuable lessons for others.

### 8. Examine interrelationships among health indicators

To improve health outcomes, it's crucial to understand how different health indicators relate to each other. We want to explore the correlations between factors like health expenditure, life expectancy, immunization rates, child mortality, and disease burden. Identifying strong or weak relationships will help shape integrated health strategies.

### 9. Investigate the relationship between government spending on health and life expectancy

Lastly we want to explore whether increased investment in health expenditure is actually driving improvements in life expectancy using trend line. Is there a clear relationship? This analysis will inform whether boosting spending is an effective lever for improving population health or if other factors need to be addressed alongside it.