# 🖥 Challenge 4YFN - MWC Barcelona 2022


## Background

Nuwefruit is a startup that wants to revolutionize people habit on everyday fruit intake. Because of this, the company is focused on home delivery, and thanks to its last mile optimization algorithm, has very low logistic costs. This lets Nuwefruit have lower prices than competition on selling fruits. Its catalog is based in more than 20 different types of fruit, the ones with better nutritional properties.

## Overview: the dataset and challenge

We will use two datasets:
 - **'CLIENT TABLE'**: Nuwefruit customer data
 - **'ORDERS TABLE'**: Order data from the customers
 
| **CLIENT TABLE** columns| Description |
|:-|:-|
| **CLIENT ID**| Unique customer id  |
| **CLIENT_SEGMENT**| Client segment  |
| **AVG CONSO**| Mean month consumption, calculated at the end of 2020 (pieces of fruit)  |
| **AVG BASKET SIZE**| Mean basket size, calculated at the end of 2020 (pieces of fruit)  |
| **RECEIVED_COMMUNICATION**| 1 = Recived a promotion / 0 = didn't receive a promotion|

> The 'CLIENT TABLE' dataset is [here](https://challenges-asset-files.s3.us-east-2.amazonaws.com/data_sets/Data-Science/4+-+events/mwc22/mwc22-client_table.csv)


|**ORDERS TABLE** columns| Description|
|:-|:-|
|**CLIENT ID**| Unique customer id | 
|**NB PRODS**| Number of 'prods' of the type of fruit (1 prod = 10 fruit pieces)|
|**ORDER ID**| Unique order id |
|**FRUIT_PRODUCT**| Type of fruit|  

> The  'ORDERS TABLE' dataset is [here](https://challenges-asset-files.s3.us-east-2.amazonaws.com/data_sets/Data-Science/4+-+events/mwc22/mwc22-orders_table.csv)

## Goals

- Make an EDA that lets you do: 
    - Analize sales and customer activity
    - Evaluate promotion impact 
- Make a predictive model that let us know the customer segment from the prediction variables used on [test_x](https://challenges-asset-files.s3.us-east-2.amazonaws.com/data_sets/Data-Science/4+-+events/mwc22/mwc22-client_table+-+test_x.csv). (We must predict the CLIENT_SEGMENT variable)


Results are in ```mwc22-client_table_test_preds.csv```


## Evaluation 
900 points -> Goals. Evaluation done on EDA and f1-score(macro) on prediction of dataset ```test_x```
200 points -> Code Quality
100 points -> Documentation