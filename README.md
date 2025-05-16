# Instacart_basket_prediction


## Introduction

This repository contains a collection of Jupyter Notebooks developed to address the Instacart Basket Analysis. This involves working with a relational dataset that tracks customer orders over time, aiming to predict which products a user is likely to purchase in their next order. The anonymized dataset includes over 3 million grocery orders from more than 200,000 Instacart users. For each user, between 4 and 100 orders are provided, detailing the products purchased in each, along with information such as the week, hour of the order, and time gaps between orders.

The repository includes the following notebooks:

1. [Data Exploration](notebooks/DataPreprocessing.ipynb): Initial analysis and understanding of the raw datasets.
2. [Customer Segmentation](notebooks/Customer_Segmentation.ipynb): Using Principal Component Analysis and K-Means Clustering to group similar customers.
3. [Association Rule Mining](notebooks/Association_Rule_Mining.ipynb): Leveraging the Apriori algorithm to uncover product and customer-related associations.

Additionally, this project tries to answer the following questions:

- Q 1: Which Grocery Items Are Popular?
- Q 2: Which Groups of Customers Are Similar?
- Q 3: Which Sets of Products Should Be Recommended To Shoppers?

## Tools and Technology

- **Interface:** Jupyter Notebook
- **Language:** Python 3.6
- **Dependencies:** pandas, numpy, scipy, matplotlib, scikit-learn (sklearn)
