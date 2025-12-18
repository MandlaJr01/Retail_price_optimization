# Retail_price_optimization
Retail Price Optimization Mini Project:  a lightweight machine learning demo that predicts demand based on price and exposes a Flask API to recommend pricing decisions using synthetic retail data.

## Retail Price Optimization Mini Project

This project demonstrates a simplified retail price optimization workflow using machine learning. It models the relationship between product price and demand using synthetic sales data and exposes a lightweight Flask API that can be used to simulate pricing decisions in a real-world retail environment.

### Problem Statement
Retailers often struggle to determine optimal pricing that balances demand and revenue. This project shows how historical pricing data can be used to model demand and support data-driven pricing decisions.

### Solution Overview
- A synthetic dataset representing price vs. units sold
- A Linear Regression model trained to estimate demand elasticity
- A Flask-based API that predicts expected demand for a given price
- A modular project structure suitable for extension into dashboards or microservices

### Technologies Used
- Python
- Pandas
- Scikit-learn
- Flask

### Use Case
This mini-project is designed as a consulting-style proof of concept. It can be extended to support:
- Dynamic pricing engines
- Retail analytics dashboards
- Scenario-based pricing simulations
- Integration with BI tools or web applications

### Disclaimer
This project uses synthetic data for demonstration purposes and is intended as an educational and portfolio example rather than a production-ready pricing system.
