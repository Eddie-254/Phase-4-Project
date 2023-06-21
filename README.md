# Phase-5-Project
Top 5 best zip codes to invest using time series


#### Contributors: [Paul Kamau](https://github.com/kamaupaul), [Hersi Yussuf](https://github.com/HersiYussuf), [Edwin Nderitu](https://github.com/Eddie-254), [Sharon Kimani](https://github.com/Sharonkimani), [Agape Gichuki](https://github.com/Muramati), [Beatrice Kirui](https://github.com/beatrice-kirui)
## Table of contents 
- [Business Understanding](#business-understanding)
- [Data preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluations)

---

## 1. Business Understanding
### Overview
Real Estate Investment Firms provide comprehensive investment advisory services, including market research, property analysis, due diligence, financial modeling, and portfolio management. Our goal is to optimize investment decisions, mitigate risks, and ensure long-term success.

The primary focus of this project is to identify opportunities in real estate markets and capitalize them to generate significant profits. We will carefully assess and mitigate risks associated with each investment in relation to zipcodes, based on some factors like market volatility. We will conduct a market analysis to identify areas of high demand and growth for optimal investment and prioritize investments with the potential substantial returns based on factors like property appreciation and market demand.

With long term value our investement strategies will focus on the ability to generate consistent cashflows overtime. Real Estate Firms can achieve a long-term partnerships with clients by achieving their financial objectives through successful real estate investments.

### Problem Statement

At Matawi Real Estate Investment firm we seek to identify the top five zip codes for potential investment opportunities. The firm aims to maximize return on investment by strategically selecting zip codes that exhibit strong growth potential and promising real estate market conditions. By leveraging data from Zillow Research,our firm intends to make data-driven investment decisions and optimize investment portfolio.

The investment firm needs to determine the top five zip codes that present the best investment opportunities based on real estate market trends and historical data. We will conduct a comprehensive analysis of various factors, such as past price trends, growth rates, market demand, and other relevant indicators to identify zip codes with the highest potential for future price appreciation.

### Objectives

#### main objective:

The main objective is to develop a forecasting model that can accurately predict real estate price movements in different zip codes and assist in identifying the most favorable locations for investment between the period of April 1996 to April 2018.
specific objectives:

To assess and mitigate potential risks associated with market volatility and economic fluctuations.
To Utilize time series analysis techniques to identify underlying patterns, trends, and seasonality in the real estate price data
To Build a time series predictive model that can forecast real estate prices for various zip codes
To Evaluate the forecasting model's performance by comparing its predictions against actual real estate prices

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
    
------
## 4. Modeling
The models include;
* Auto Regressive model(AR)
* ARMA model
* ARIMA model
* SARIMA model

-------
## 5. Evaluation 
while the AIC provides a measure of model complexity, the RMSE assesses predictive accuracy. If the SARIMA model exhibits a lower RMSE despite a higher AIC, it indicates improved forecasting performance and can be considered the better model.


## 6. Conclusion



---

## 7. Recommmendations

---
 
