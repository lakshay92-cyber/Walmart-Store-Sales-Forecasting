# Walmart-Store-Sales-Forecasting

#### Business Context:
The objective is predicting store sales using historical markdown data.
One challenge of modelling retail data is the need to make decisions based on limited
history. If Christmas comes but once a year, so does the chance to see how strategic
decisions impacted the bottom line.

#### Data Availability & Business Problem:
You are provided with historical sales data for 45 Walmart stores located in different
regions. Each store contains a number of departments, and you are tasked with predicting
the department-wide sales for each store.

In addition, Walmart runs several promotional markdown events throughout the year.
These markdowns precede prominent holidays, the four largest of which are the Super
Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are
weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge
presented by this competition is modelling the effects of markdowns on these holiday
weeks in the absence of complete/ideal historical data.
* stores.csv: This file contains anonymized information about the 45 stores, indicating
the type and size of store.
* train.csv: This is the historical training data, which covers to 2010-02-05 to 2012-11-

* Within this file you will find the following fields:
  * Store - the store number
  * Dept - the department number
  * Date - the week
  * Weekly_Sales - sales for the given department in the given store
  * IsHoliday - whether the week is a special holiday week

* test.csv: This file is identical to train.csv, except we have withheld the weekly sales.
You must predict the sales for each triplet of store, department, and date in this file.
* features.csv: This file contains additional data related to the store, department, and
regional activity for the given dates. 
* It contains the following fields:
  * Store - the store number
  * Date - the week
  * Temperature - average temperature in the region
  * Fuel_Price - cost of fuel in the region
