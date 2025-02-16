# S&P 500 Stock Analysis Python

## Overview
This project conducts a thorough analysis of S&P 500 stock data, exploring trends, moving averages, and correlations among tech giants, providing insights for investors.

## Approach

- Installation
- Data Collection
- Data Analysis
    - Price Change Analysis
    - Moving Average
    - Closing Price Change in Apple, Netflix & Amazon Stock
    - Resampling Analysis
    - Correlation Among Tech Companies
    - Daily Change vs. Daily Returns
      
- Packages installed
    - pandas
    - seaborn
    - numpy
    - matplotlib
    - plotly

## Data Collection

Using glob module to search CSV files and use it for our need
import glob

## Data Analysis

### Price Change Analysis
Analysing the change in prices of the stock overtime

![image](https://github.com/user-attachments/assets/1eecb172-5b6c-48a0-a23e-1532ae279a5e)

### Moving Average
Analysing the Moving average of the various stocks 

![image](https://github.com/user-attachments/assets/ce360804-3584-4cb9-8e8f-ef9f1259634b)

### Closing Price Change in Apple, Netflix & Amazon Stock

Analysing Closing price change in Apple stock 

![image](https://github.com/user-attachments/assets/19e19413-287a-443b-8aff-8b92fd44fca6)

Analysing Closing price change in Netflix stock

![image](https://github.com/user-attachments/assets/3089493b-ae56-4d3a-9935-105ad93ab9b0)

Analysing Closing price change in Amazon stock

![image](https://github.com/user-attachments/assets/6c1ba282-65c6-4f65-8ba7-5497befa7b7a)

Resampling Analysis

Performing resampling analysis of closing price of Apple 

Resampling data on Date basis

![image](https://github.com/user-attachments/assets/8606a488-4cca-4586-a3a9-ea27af7bffe0)

Resampling data on Montly basis

![image](https://github.com/user-attachments/assets/35d2be62-897a-472b-8a16-34be8d1c9d75)

Resampling data on Yearly basis

![image](https://github.com/user-attachments/assets/01120b49-5bd0-4599-81dc-e8f162fa078d)

Resampling data on Quarterly basis

![image](https://github.com/user-attachments/assets/3c420252-d3d4-42bd-b18c-4a34783e98c2)

## Correlation Among Tech Companies

Analysing Whether closing prices of these tech companies (Amazon,Apple,Facebook,Google,Netflix,Microsoft) are correlated or not

### Pair Plot
![image](https://github.com/user-attachments/assets/8d8cc46d-7349-44ea-9fa2-7cef10492c46)

### Heatmap

![image](https://github.com/user-attachments/assets/7d048795-e214-4403-92ec-b5334f168935)

Conclusions : Closing price of Google and Microsoft, Facebook and Microsoft, Google and Facebook, Amazon and Google are well correlated. Closing prices have a co-relation of 0.97

### Daily Change vs. Daily Returns

Analysing Whether Daily change in Closing price of stocks or Daily Returns in Stock are co-related or not

### Pair Grid

![image](https://github.com/user-attachments/assets/7d6df872-c980-4def-8f14-8d85337d0327)

Amazon and Google stocks has highest correlation between them
Conclusion: If Amazon stocks decreases, then there is a 54% probablity that Google stocks also decreases
