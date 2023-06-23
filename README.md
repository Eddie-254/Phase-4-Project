# Phase-5-Project: Zillow Dataset Time Series
![hottest-ZIP-codes-ranked](https://github.com/Eddie-254/Phase-4-Project/assets/40391537/6e6a18e9-43bc-42c3-aad8-5e4566322102)



 ##### Contributors: [Paul Kamau](https://github.com/kamaupaul), [Hersi Yussuf](https://github.com/HersiYussuf), [Edwin Nderitu](https://github.com/Eddie-254), [Sharon Kimani](https://github.com/Sharonkimani), [Agape Gichuki](https://github.com/Muramati), [Beatrice Kirui](https://github.com/beatrice-kirui)
## Table of contents 
- [Business Understanding](#business-understanding)
- [Data preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluations)

---

## 1. Business Understanding
### Overview
Real Estate Investment Firms provide comprehensive investment advisory services, including market research, property analysis, due diligence, financial modeling, and portfolio management.
Our goal is to optimize investment decisions, mitigate risks, and ensure long-term success.

The primary focus of this project is to identify opportunities in real estate markets and capitalize on them to generate significant profits. We will carefully assess and mitigate risks associated with each investment based on some factors like market volatility.
We will conduct a market analysis to identify areas of high demand and growth for optimal investment and prioritize investments with potential substantial returns based on factors like property appreciation and market demand.

With long-term value, our investment strategies will focus on the ability to generate consistent cashflows overtime. Real Estate Firms can achieve long-term partnerships with clients by achieving their financial objectives through successful real estate investments.


### Problem Statement

At Matawi Real Estate Investment firm, the key problem is to identify the top five areas that present the best
investment opportunities in the real estate market. The firm aims to maximize return on investment by
strategically selecting areas with strong growth potential and favorable real estate market conditions.

To address this problem, the firm needs to leverage data from trusted sources like Zillow Research and
conduct a comprehensive analysis of various factors. These factors include past price trends, growth rates,
market demand, and other relevant indicators to determine the areas with the highest potential for future
price appreciation.

By making data-driven investment decisions based on the analysis, the firm aims to optimize its investment
portfolio and achieve maximum returns for its clients.

### Objectives

#### Main objective:

* The main objective is to develop a forecasting model that can accurately predict real estate price movements in different areas and assist in identifying the most favorable locations for investment between the period of April 1996 to April 2018.

#### Specific objectives:

* To assess and mitigate potential risks associated with market volatility and economic fluctuations.
* To Utilize time series analysis techniques to identify underlying patterns, trends, and seasonality in the real estate price data
* To Build a time series predictive model that can forecast real estate prices.
* To Evaluate the forecasting model's performance by comparing its predictions against actual real estate prices
* To forecast house prices in the next subsequent years.


## 2. Data Understanding

### Overview
The dataset used in this project consists of historic median house prices from various regions in the USA. It covers a time period of 22 years, specifically from April 1996 to April 2018. The dataset was obtained from the Zillow website. [Zillow website](https://github.com/learn-co-curriculum/dsc-phase-4-choosing-a-dataset/blob/main/time-series/zillow_data.csv) 

### Data Description
This data contains 272 columns and 14,723 rows. It has the following columns and descriptions;

`RegionID`: A unique identifier for each region.

`RegionName`: The names of the regions, represented by zip codes.

`City`: The corresponding city names for each region.

`State`: The names of the states where the regions are located.

`Metro`: The names of the metropolitan areas associated with the regions.

`County Name`: The names of the counties where the regions are situated.

`Size Rank`: The ranking of the zip codes based on urbanization.

------
## 3. Data Preparation
Within our data preparation phase, we performed the following tasks:
* Clean Data
* Checking Duplicates
* Filled Missing Values
* Feature Engineering 
    
------
## 4. EDA
The following analysis was performed on the data:
* Univariate Analysis
* Bivariate Analysis
* Multi-Variate Analysis
* Time Series Analysis

------
## 5. Modeling
Time series modeling was chosen as it refers to building a machine learning model that can auto-generate future predictions based on existing or historical data which was our dataset.
The models include;
* Auto Regressive model(Base Model)
* ARIMA model
* SARIMA model

-------
## 5. Evaluation 
Our success metrics are; Root Mean Squared Error, AIC and BIC. The ARMA model has the lowest AIC, BIC and RMSE hence we will use this model for forecasting.


## 6. Conclusions
* The housing market in New York, Los Angeles, and other top cities, states, metros, and counties demonstrates high activity and asignificant number of houses.

* Return on investment (ROI) and house prices exhibit positively skewed distributions, with outliers indicating higher returns and extremely high-priced houses.

* There is a strong positive relationship between ROI and the coefficient of variation (CV), implying that higher risk is associated with higher returns.

* New York consistently stands out as the location with the highest ROI across different levels of analysis, such as states, metros, and counties.

* San Francisco, Los Angeles, and other specific cities, states, metros, and counties offer a combination of high ROI and lower risk, making them attractive for real estate investment.


---

## 7. Recommendations
* Consider investing in real estate in New York, particularly in cities like San Francisco and Los Angeles, which have shown high ROI and relatively lower risk.

* Focus on short-term investment opportunities to capitalize on the predicted high increment in house prices for the next year.

* Adopt a conservative approach during the anticipated high decrement period of the following three years and carefully assess market conditions before making major investments.

* Consider selling properties at their peak value before the reduced increment period to maximize profits and mitigate potential losses.

* Diversify the portfolio across different locations and property types to spread risk and minimize exposure to market downturns.

* Monitor the real estate market closely, staying updated on trends, economic indicators, and regulatory developments to make informed decisions.

* Mitigate risks through thorough due diligence, assessing property quality, and conducting proper market research.
---
 
