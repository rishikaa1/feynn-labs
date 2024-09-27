# OptiChain: AI-Driven Solution for Supply Chain Optimization for SMEs

This repository contains all the essential files for the **OptiChain** project, including the report, dataset, and code implementation for the development and business/financial modelling of the prototype.

## Project Overview
**OptiChain** integrates AI-powered machine learning models and optimization algorithms to enhance the following supply chain processes:
- Demand Forecasting
- Inventory Optimization
- Supplier Management
- Logistics Planning

The project addresses common challenges faced by SMEs, such as inefficient resource allocation, fragmented data, and limited access to advanced technologies, offering a scalable and cost-effective solution.

## Files in the Repository

1. `Report.pdf!`: A comprehensive report detailing the OptiChain platform, its core functionalities, business model, technical architecture, and financial modeling approach.
2. `Demand_Forecasting_Inventory_Logistics_Optimization.ipynb`: Colab notebook containing the code for implementing the machine learning models, including:
     - LSTM-based demand forecasting
     - Economic Order Quantity (EOQ) for inventory optimization
     - Dijkstra’s algorithm for logistics route optimization
3. `train.csv.zip`: Dataset containing sales data, which is used for training and testing the demand forecasting and logistics optimization models. The dataset contains the following columns:
     - `date`: Sales record date
     - `store_nbr`: Unique identifier for each store
     - `family`: Product category

## Requirements

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `tensorflow.keras`
- `heapq`

## Results and Insights

- **Demand Forecasting:** Predict future sales based on historical data using LSTM, providing insight into expected demand fluctuations.
- **Optimal Inventory Levels:**  Use the EOQ model to determine the most cost-effective order quantities to minimize holding and order costs.
- **Logistics Optimization:** Leverage Dijkstra’s algorithm to find the most efficient routes for transporting goods, minimizing logistics costs.

## License
This project is licensed under the [Apache License Version 2.0](../LICENSE)
