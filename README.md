# Customer Segmentation Using Recency, Frequency, Monetary (RFM) Analysis 

This project performs customer segmentation using RFM analysis on an online retail dataset. The workflow is implemented in a Jupyter Notebook using Python and Plotly for interactive visualizations.

## Features

- **Data Cleaning:** Removes rows with missing `CustomerID` values for accurate segmentation.
- **Feature Engineering:** Calculates transaction amounts and converts date columns.
- **RFM Metrics Calculation:** Aggregates Recency, Frequency, and Monetary values for each customer.
- **RFM Scoring:** Assigns scores based on quantiles for each metric.
- **Segmentation:** Classifies customers into business-relevant segments:
  - Low-Value, Mid-Value, High-Value
  - Lost, Can't Lose, At Risk, Potential Loyal, VIP/Loyal
- **Visualization:** Interactive bar charts and treemaps to show segment distributions.
- **Actionable Insights:** Recommendations for marketing and retention strategies.

## Usage
  1. Open `rfm.ipynb` in VS Code or Jupyter Notebook.
  2. Ensure `online_retail.csv` is in the same directory.
  3. Run the notebook cells sequentially to reproduce the analysis and visualizations.
     
## Requirements

- Python 3.11+
- pandas
- plotly

Install dependencies with:

```bash
pip install pandas plotly
```
