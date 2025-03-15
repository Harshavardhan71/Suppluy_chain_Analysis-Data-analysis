# Supply Chain Analysis

## Project Overview
This project performs an in-depth analysis of supply chain data using a dataset sourced from Kaggle. It examines key aspects such as cost analysis, supply chain efficiency, logistics, quality control, and production analysis. Additionally, it uses machine learning to predict production volumes and optimize lead times.

## Dataset
The dataset used for this analysis contains information about:
- Product types
- Manufacturing costs
- Revenue generated
- Lead times
- Transportation modes
- Routes
- Costs
- Defect rates
- Stock levels
- Sales quantities
- Production volumes

## Analysis Performed

### 1. Cost Analysis
#### 1.1 Most Costly Products to Produce
- Calculates the total manufacturing costs per product type.
- Identifies the most expensive products to produce.

#### 1.2 Overall Profitability
- Computes profitability as **Revenue Generated - Manufacturing Costs**.
- Analyzes which product types are the most profitable.

### 2. Supply Chain Analysis
#### Average Lead Times
- Determines the average lead time for each product type.
- Identifies potential delays in the supply chain.

### 3. Logistics Analysis
#### 3.1 Most Common Transportation Modes
- Identifies the most frequently used transportation modes.

#### 3.2 Transportation Modes and Their Impact
- Analyzes average lead times and costs associated with different transportation modes.

#### 3.3 Common Routes and Their Impact
- Determines the most commonly used transportation routes.
- Assesses the impact of different routes on lead times and costs.

### 4. Quality Analysis
#### Average Defect Rate by Product Type
- Computes the average defect rate for each product type.
- Helps in identifying quality control issues.

### 5. Production Analysis
#### Production Volumes and Stock Levels/Sales Quantities
- Uses **Linear Regression** to predict production volumes based on stock levels and sales quantities.
- Prints the coefficients and intercept of the model.
- Evaluates model performance using **R-squared (R2)** and **Root Mean Squared Error (RMSE)**.

### 6. Optimization Questions
#### Reducing Lead Times
- Identifies inefficiencies in lead times by analyzing their distribution.
- Flags long lead times for further investigation and potential process improvements.

## Technologies Used
- **Python**
- **Pandas** (Data manipulation and analysis)
- **Matplotlib** (Data visualization)
- **NumPy** (Mathematical computations)
- **Scikit-Learn** (Machine learning for regression analysis)

## Results and Insights
This project provides actionable insights into optimizing supply chain processes by analyzing costs, lead times, logistics, and production volumes. The machine learning model predicts production needs based on stock levels and sales data, helping in efficient resource planning.


