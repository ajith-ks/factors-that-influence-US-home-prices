# U.S. Home Prices Analysis

## Aim
The aim of this project is to build a predictive model using publicly available data to understand the key supply-demand factors that could influence U.S. home prices. We will use these factors to explain how they have affected home prices over the last 20 years (from 2000 to 2020).

## Dataset
We have created a dataset with the following features:

1. **Home Price Index (Home_Price_Index):** 
   - This feature serves as the target variable in the dataset, representing U.S. home prices.
   - Source of data: [Home_Price_Index](https://fred.stlouisfed.org/series/CSUSHPISA)

2. **Observation Date:** 
   - These are the dates of observations (Annual observations from the year 2000 to 2020).

3. **Unemployment Rate:** 
   - This feature provides the unemployment rate of the USA from the year 2000 to 2020.
   - Source of data: [Unemployment_Rate](https://fred.stlouisfed.org/series/UNRATE)

4. **GDP (Gross Domestic Product):** 
   - This feature gives the Gross Domestic Product value of the USA from the year 2000 to 2020.
   - Source of data: [GDP](https://fred.stlouisfed.org/series/GDP)

5. **Building Permits:** 
   - This feature provides the values of total housing permits issued in the USA from 2000 to 2020 (Unit: Thousands of units).
   - Source of data: [Building_Permits](https://fred.stlouisfed.org/series/PERMIT)

6. **Population Growth (Population):** 
   - This feature gives information about the population growth of the USA (Unit: Thousands).
   - Source of data: [Population](https://fred.stlouisfed.org/series/POPTHM#0)

7. **Real GDP Growth (Real_GDP_Growth):** 
   - This feature represents whether the year was going through a recession or not (0 -> represents recession, 1 -> represents no recession).
   - Source of data: [Real_GDP_Growth](https://fred.stlouisfed.org/series/JHDUSRGDPBR)

8. **State Tax Rate (State_Tax_Rate):** 
   - This feature provides the values of taxes homeowners had to pay during the observation date (Unit: Thousands).
   - Source of data: [State_Tax_Rate](https://fred.stlouisfed.org/series/CXUSTATETAXLB1702M)

9. **Life Expectancy (Life_Expectancy):** 
   - This feature gives the value of life expectancy at birth for the United States (Unit: Years).
   - Source of data: [Life_Expectancy](https://fred.stlouisfed.org/series/SPDYNLE00INUSA)

10. **30-Year Mortgage Rate (30_Year_Mortgage_Rate):** 
    - This feature provides the values of the average mortgage rate in the United States (Unit: Percent).
    - Source of data: [30_Year_Mortgage_Rate](https://fred.stlouisfed.org/series/MORTGAGE30US)

11. **Housing Consumer Price Index (Housing_CPI):** 
    - The Housing CPI measures changes over time in the prices paid by consumers for a representative basket of goods and services.
    - Source of data: [Housing_CPI](https://fred.stlouisfed.org/series/CPIHOSSL)

## Usage
You can use this dataset and the associated code to analyze how various economic and demographic factors have influenced U.S. home prices over the past two decades. This analysis can provide valuable insights into the housing market and its relationship with broader economic trends.
