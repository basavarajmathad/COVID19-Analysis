# 🌍 COVID-19 Global Analysis Dashboard 📊

## Overview
This **Power BI Dashboard** provides an interactive and data-driven analysis of **COVID-19** statistics across the globe. The dataset was **scraped from the Worldometer website** using Python and **BeautifulSoup**, then analyzed and visualized in Power BI.

## 🔍 Key Features
✅ **Web Scraping**: Extracted COVID-19 data from [Worldometer](https://www.worldometers.info/coronavirus/) using **BeautifulSoup**.  
✅ **Summary Metrics**: Total cases, deaths, recoveries, and active cases.  
✅ **Country-wise & Continent-wise Analysis**: Visual breakdown of cases, deaths, and recoveries.  
✅ **Geographical Visualization**: A world map displaying case distributions.  
✅ **Trend Insights**: Recovery rate, fatality rate, and serious case analysis.  
✅ **Filters & Slicers**: Interactive controls to filter data by region and category.  

## 📂 Files in Repository
| File Name                  | Description |
|----------------------------|-------------|
| `wordometer direct.pbix`  | Power BI dashboard file |
| `covid19_scraper.py`  | Python script to scrape data from Worldometer |

## 🛠️ Tools & Technologies
- **Python** - Web scraping and data preprocessing  
- **BeautifulSoup** - Extracting data from Worldometer  
- **Pandas** - Data cleaning and manipulation  
- **Power BI** - Data visualization & dashboard creation  
- **DAX** - Used for calculations and measures  

## 🔍 Web Scraping Process
1. **Fetched COVID-19 data** from [Worldometer](https://www.worldometers.info/coronavirus/) using **requests** and **BeautifulSoup**.  
2. **Parsed the HTML structure** to extract relevant tables and statistics.  
3. **Cleaned and structured the data** using **Pandas** before saving it to CSV/Excel.  
4. **Imported the cleaned data into Power BI** for visualization and analysis.  

## 📈 Insights & Findings
- **USA, Brazil, and India** reported the highest number of total cases.  
- **Europe & Asia** had the highest fatalities, while **South America** showed a strong recovery rate.  
- **Testing rates** varied significantly across countries, impacting case detection.  
- **Seasonal trends and policy changes** influenced case numbers.  

