# Customer Segmentation for Marketing Strategies

This project focuses on customer segmentation using machine learning techniques to develop targeted marketing strategies. By analyzing customer data, the project aims to group customers based on their purchasing behavior, which can help businesses tailor their marketing efforts to different customer segments.

## Project Overview

Customer segmentation is a crucial aspect of marketing strategy, allowing businesses to identify distinct groups within their customer base and tailor their efforts accordingly. In this project, we use clustering algorithms like **K-Means** and **DBSCAN** to segment customers based on their transactional data.

## Dataset Information

The dataset used in this project is an online retail dataset containing transactional data. Each row represents an individual transaction, with the following features:

- **InvoiceNo**: Unique transaction identifier.
- **StockCode**: Unique product identifier.
- **Description**: Product name or type.
- **Quantity**: Number of units purchased.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique customer identifier.
- **Country**: Customer's country.

## Requirements

To run the project, you need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
