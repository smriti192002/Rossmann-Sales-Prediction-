# Project Title - Sales Prediction : Predicting sales of a major store chain Rossmann

![104977231-ca344600-59dd-11eb-94c4-26f431bc2802](https://user-images.githubusercontent.com/88886118/213765233-a9265fb0-14de-4d5c-83ff-2c55e7c6ec4c.png)

---
## Contents <p id="contents"></p>
- <a href="#bquestions">Business Questions</a>
  - <a href="#business_impact">Business Impact</a>
- <a href="#methodology">Methodology</a>
  - <a href="#data_collect">Data Collect</a>
  - <a href="#data_cleaning">Data Cleaning</a>
    - <a href="#data_description">Data Description</a>
- <a href="#data_exploration">Data Exploration</a>
 
## 📝 Problem Statement <p id="bquestions"></p>

Rossmann operates over 3,000 drug stores in 7 European countries.  Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, 
You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column . Note that some stores in the dataset were temporarily closed for refurbishment.

## How it might be helpful for business? <p id="business_impact"></p>

Many of these managers contacted me for consult the data to make the prediction for their stores. So, I went looking for the real stakeholder to understand the main reason for this sales forecast. Talking to managers, they told me that was a request from the CFO at a meeting with all managers.

When discussing with the CFO, he informs me that wants to know the store sales forecast because wants to renovate them, and he would like to know how much money will have in cash to carry out the construction. I understod the main problem and start looking for the data that will help me make this prediction.

As this is a problem originating from a Kaggle competition, the data are available through their platform, and it is not necessary to use extraction from databases and other sources.

## 💻 Methodology <p id="methodology"></p>
![sales_forecast_32f42ee760](https://user-images.githubusercontent.com/88886118/213775274-3112ea1f-e468-4a77-9b02-8c5d34a47ec3.png)

## DATA COLLECT <p id="data_collect"></p>

The data used in this project are available through the Kaggle platform, and can be find [here](https://www.kaggle.com/c/rossmann-store-sales/data). But, if it were a real company environment, this data would be collected through database queries, and other sources of information.

## DATA CLEANING <p id="data_cleaning"></p>

Cleaning the dataset downloaded from the previous step, performing operations such as:

### Data Description <p id="data_description"></p>

  - Check the size and type of the data.
  - Check for the existence of missing values, and if so, use an approach to fill in these values.
    - *In this step i found some columns with missing values, and filled them thinking about the business.*
  - Standardize the types of variables.

## EXPLORATORY DATA ANALYSIS <p id="data_exploration"></p>

The exploratory data analysis proposes to analyze how the variables map the phenomenon we want to model, and what is the strength of this impact. Proposed basically for 3 objectives:

- Gain business experience.
- Validate business hypotheses and generate insights.
- Identify variables that are important to the model.

![download (41)](https://user-images.githubusercontent.com/88886118/216097495-be0769d6-7087-4a5b-ad7b-410bf011f3cc.png)

Relation seems to be linear between customers and sales but seems to have high variance
Also Graph helps us conclude that although there are some stores that have a same customer visit still some have higher sales and some have lower sales
It can be dependable on many factors like competitors distance, promo,etc
