# Brazilian E-Commerce Public Dataset by Olist
Welcome! This is a Brazilian ecommerce public dataset of orders made at Olist Store. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. We also released a geolocation dataset that relates Brazilian zip codes to lat/lng coordinates.
This is real commercial data, it has been anonymised, and references to the companies and partners in the review text have been replaced with the names of Game of Thrones great houses.

## Context
This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. See more on our website: www.olist.com
After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date is due, the customer gets a satisfaction survey by email where he can give a note for the purchase experience and write down some comments.

## Data Schema
The data is divided in multiple datasets for better understanding and organization. Please refer to the following data schema when working with it:
![image](https://i.imgur.com/HRhd2Y0.png)

## Classified Dataset
We had previously released a classified dataset, but we removed it at Version 6. We intend to release it again as a new dataset with a new data schema. While we don't finish it, you may use the classified dataset available at the Version 5 or previous.

## Acknowledgements
Thanks to Olist for releasing this dataset.

## Contribution to the project
Performed Exploratory Data Analysis on data being provided.
Created Recommendation Engine that recommends more products to customer who had recently placed an order of any product. The products being recommended based on previous purchase and is determined by finding the association between purchased product along with all the products sold in past.
Added Loggers to all the files to ensure proper workflow of model as well as created an UI to show analysis being done on the data.
