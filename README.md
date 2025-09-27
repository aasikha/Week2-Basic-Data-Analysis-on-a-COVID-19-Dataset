# COVID-19 Early Data Analysis

This repository contains a brief analysis of early COVID-19 data using the dataset `2019_nCoV_data.csv`.

## Dataset
- Source: Kaggle (`2019_nCoV_data.csv`)  
- Contains information on confirmed cases, deaths, and recoveries by country/region, province/state, and date.  
- Note: Some missing values exist in the `Province/State` column.  

## Libraries Used
- `pandas` – for data manipulation  
- `numpy` – for numerical operations  
- `matplotlib` & `seaborn` – for visualizations  

## Key Observations
- Early outbreak was concentrated in China, especially Hubei province.  
- Top affected countries include: China, Italy, South Korea, Iran, USA.  
- Global confirmed cases showed an exponential rise initially, then plateaued in some regions.  
- Recovery rate generally lags behind confirmed cases; death rate varies by country.  
- Visualizations include line plots (confirmed, deaths, recovered), pie charts (recovered vs deaths), and bar charts (top affected countries).  

## Visualizations
- Trend of confirmed, deaths, and recovered cases over time.  
- Distribution of recovered vs deaths globally.  
- Top 10 countries by confirmed cases.

## Usage
1. Clone the repository:
```bash
git clone <repository_url>
