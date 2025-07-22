# Customer Segmentation Using RFM Analysis

## Overview

This project applies **RFM (Recency, Frequency, Monetary)** analysis to transactional data to segment customers based on their purchasing behavior. The goal is to identify high-value customers, those at risk of churn, and other key customer groups for strategic decision-making in marketing and customer retention.

RFM stands for:
- **Recency** – How recently a customer made a purchase
- **Frequency** – How often they purchase
- **Monetary** – How much they spend

## Objectives

- Load and clean customer transaction data
- Calculate Recency, Frequency, and Monetary values for each customer
- Assign RFM scores and create segments
- Visualize the distribution and segment characteristics
- Use the insights to support customer relationship strategies

## Dataset

> The project uses a CSV file containing transactional data.  
> It includes fields such as:
- Customer ID
- Invoice Date
- Invoice Number
- Quantity
- Unit Price
- Country

## Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## Steps Performed

1. **Data Preprocessing**
   - Handle missing values
   - Remove negative or cancelled transactions

2. **RFM Metric Calculation**
   - **Recency**: Days since last purchase
   - **Frequency**: Number of transactions
   - **Monetary**: Total spending

3. **Scoring and Segmentation**
   - Assign scores (1–5) for each RFM metric
   - Combine to create RFM scores (e.g., 555 = best customers)
   - Define customer segments using rules or quantiles

4. **Data Visualization**
   - Histograms and boxplots for RFM distributions
   - Segment-wise customer counts

## Results

- Identified segments such as:
  - Champions
  - Loyal Customers
  - At Risk
  - New Customers
  - Lost

- Provided strategic insights for targeted marketing

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/rfm-analysis.git
cd rfm-analysis

2. Open the Jupyter Notebook:
```bash
jupyter notebook RFM.ipynb

3. Make sure to install dependencies:
```bash
pip install pandas numpy matplotlib seaborn

4. Replace or use the provided sample dataset in CSV format.
