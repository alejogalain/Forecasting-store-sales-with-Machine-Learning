# Forecasting-store-sales-with-Machine-Learning

## 1. Problem definition
The goal is to forecast store sales on data from Corporación Favorita (a large Ecuadorian-based grocery retailer), using time-series forecasting.

## 2. Data
The data is downloaded from Kaggle: https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data
There are two main datasets: train and test.
The test data comprises the 15 days after the training data.

## 3. Evaluation
The evaluation metric is the Root Mean Squared Logarithmic Error (RMSLE).

## 4. Features

The training data has the following time series features: store_nbr, family, onpromotion and the target sales:
*  store_nbr - identifies the store at which the products are sold
*  family - identifies the type of product sold
* sales - gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units.
* onpromotion - gives the total number of items in a product family that were being promoted at a store at a given date.

The test data has the same features as the training data. 

Additional information:
* Store metadata, including city, state, type, and cluster (cluster is a grouping of similar stores)
* Daily oil price. Includes values during both the train and test data timeframes.
* Holidays and Events, with metadata
