# Canada_Trade
Analysis of Canada's international trade based on province, principal trade partners, product classification system starting from 1997 up to 2022.

## **Overview**
This project was designed to create a dashboard that can be integrated into Statistics Canada's webpage that depicts Canada's trade data. This dashboard facilitates easy and prompt access to the most important values concerning Canada's trade based on the total trade, domestic export, import, re-export, trade balance, trade by province, trade by industry, trade by principal trading partner, and the ability to filter on the period of interest.


## **Tech Stack**
  * Python
  * Microsoft Power BI


## **Methods**

#### **Python**
In this project python was used to wrangle the dataset before importing it into Microsoft Power BI. The following changes were applied to the '1210011901.csv' dataset:

  * Removed columns in the dataset that were irrelevant to the analysis.
  * Removed rows that would lead to double counting.
  * Scaled the values column to have the values depicting the accurate dollar value.


#### **Microsoft Power BI**

**Dashboard**

![Trade_Dashboard](https://github.com/OmarQasem94/Sales_Insights/blob/main/Images/Dashboard_Photo.png)

The dashboard depicts the following:

  * Total Trade
  * Trade Balance
  * Trade Type 
  * Value of trade per province
  * Value of trade per principal trading partner
  * Value of trade per industry
  * Date filter


## **Citations**

Statistics Canada. (2022). Table 12-10-0119-01 International Merchandise trade by province, commodity, and Principal Trade Partner [Data Table].
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1210011901

