# Dehradun Weather Analysis (2015–2023) — EDA Project

## About the Project
This is an Exploratory Data Analysis (EDA) project on real historical daily weather 
data for Dehradun, Uttarakhand. The goal was to explore climate patterns, answer 
specific questions about the weather, and present findings through charts.

No machine learning was used. This is pure data analysis.

## About the Data
- Source: Kaggle (multiple yearly CSV files)
- Years covered: 2015 to 2023
- Files: 5 CSV files combined into one dataset
- Final shape after cleaning: 3,287 rows × 30 columns
- Each row represents one day of weather data

## Questions Explored
1. What is the average temperature for each month in Dehradun?
2. Which month receives the most rainfall?
3. Is Dehradun getting hotter over the years?
4. How many days per year have humidity above 80%?
5. Which months have the largest daily temperature swings?

## Key Findings
- **Temperature:** June is the hottest month (~28°C) and January is the coldest. 
  Temperatures follow a clear seasonal rise and fall pattern.
- **Rainfall:** July and August receive the most rainfall, consistent with the 
  Indian monsoon season hitting Dehradun between June and September.
- **Yearly trend:** There is no consistent upward trend in temperature from 
  2015–2023. Temperatures fluctuate year to year, with 2020 being the 
  coldest year, likely influenced by reduced activity during the global lockdown.
- **Humidity:** Humid days (above 80%) vary significantly by year, peaking at 
  around 160 days in 2021. No clear long-term trend was observed.
- **Temperature range:** April and May have the largest gap between daily high 
  and low temperatures, while July and August have the smallest, as monsoon 
  clouds moderate both daytime heat and nighttime cold.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code
