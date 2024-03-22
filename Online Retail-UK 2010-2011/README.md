# Summary

The dataset of online retail transactions holds a wealth of potential insights, but like any real-world data, its secrets lie veiled beneath a seemingly clean surface. This dataset, with its unique invoice numbers, product codes, quantities, prices, customer information, and transaction dates, promises to reveal patterns of customer behavior, sales trends, and product relationships. The claim of no missing values presents an intriguing challenge, as data cleaning is a cornerstone of reliable analysis. Let's dive deeper and uncover hidden inconsistencies, paving the way for a robust exploration of this e-commerce landscape.



# Description

## Online Retail

https://archive.ics.uci.edu/dataset/352/online+retail

Chen,Daqing.
(2015). Online Retail. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.

@misc{misc_online_retail_352,

  author       = {Chen,Daqing},

  title        = {{Online Retail}},

  year         = {2015},

  howpublished = {UCI Machine Learning
Repository},

  note         = {{DOI}: https://doi.org/10.24432/C5BW33}

}

This is a
transnational data set which contains all the transactions occurring between
01/12/2010 and 09/12/2011 for a UK-based and registered non-store online
retail.

| **Variable Name** | **Role** | **Type**    | **Description**                                                                                                                       | **Units** | **Missing Values** |
| ----------------- | -------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------- | ------------------ |
| InvoiceNo         | ID       | Categorical | a 6-digit integral number uniquely assigned to each<br> transaction. If this code starts with letter 'c', it indicates a cancellation |           | no                 |
| StockCode         | ID       | Categorical | a 5-digit integral number uniquely assigned to each<br> distinct product                                                              |           | no                 |
| Description       | Feature  | Categorical | product name                                                                                                                          |           | no                 |
| Quantity          | Feature  | Integer     | the quantities of each product (item) per transaction                                                                                 |           | no                 |
| InvoiceDate       | Feature  | Date        | the day and time when each transaction was generated                                                                                  |           | no                 |
| UnitPrice         | Feature  | Continuous  | product price per unit                                                                                                                | sterling  | no                 |
| CustomerID        | Feature  | Categorical | a 5-digit integral number uniquely assigned to each<br> customer                                                                      |           | no                 |
| Country           | Feature  | Categorical | the name of the country where each customer resides                                                                                   |           | no                 |
