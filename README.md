# maven-toys
An analysis on the expansion plan for Maven Toys

## Introduction
Maven Toys is a  fictitious chain of toy stores in Mexico with 50 stores in 29 cities in 4 different states. They are looking at expanding the businesss to further increase revenue and profits. This project was carried out to aid the decision making of stakeholders at MAVEN TOYS on expansion of company in new states by providing data driven insights and solutions from past and current records.

### Aims and Objectives
The following questions are the "whats" of the project:
* Which locations are feasible to open new stores?
* Which products and prodcut categories are the most profitable to stock up the new stores with?
* Determine the seasonal trends or patterns
* How to further boost sales and revenue generally??

### Data Sourcing
The dataset was gotten from [Kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/toy-sales) including information about products, stores, daily sales transactions, and current inventory levels

### Extraction Transformation and Loading (ETL) and Data Cleaning
Upon extracting the dataset to local machine, the dataset was imported into powerbi power query for Transformation. Duplicates, nulls and blanks were removed, typo errors were corrected and columns were formatted to the appropriate format.

### Data Analysis

From the sales table the following were calculated using DAX;
* Total Revenue
** ![Total Revenue](https://user-images.githubusercontent.com/105971924/208591855-8f8d497c-e66d-4de9-b2d7-9ef956531abf.png)

* Total Cost
![Total Cost](https://user-images.githubusercontent.com/105971924/208591899-67f37aed-e794-4fc9-8b41-0b310a9265bb.png)

* Total Profit
![Profit](https://user-images.githubusercontent.com/105971924/208592140-223dee81-67af-445b-a5a4-7609041df369.png)

* Gross Profit Margin
* ![GPM](https://user-images.githubusercontent.com/105971924/208592196-2314ecca-373d-410c-aaf3-61ed593400e3.png)

* Avg. Transaction Value
![ATV](https://user-images.githubusercontent.com/105971924/208592455-2a565e8a-6f37-4562-84fa-6fa9186f4341.png)

* Avg. Unit sold
![AUS](https://user-images.githubusercontent.com/105971924/208592926-f1d00946-64bb-4096-b466-eff9c1a0d9b2.png)

From the stores table;
* Distinct count of Stores
* Distinct count of Locations
* Total count of sales made
* Average Revenue per store
![Rev per store](https://user-images.githubusercontent.com/105971924/208593383-dee1b63d-2bab-4776-b61f-ddf0e9e8b8b6.png)

