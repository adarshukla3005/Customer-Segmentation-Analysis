# Customer Segmentation Analysis

## Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques, specifically K-Means clustering. The goal is to analyze customer data from a mall to identify distinct groups of customers based on their demographic and behavioral attributes. These insights can help businesses target marketing strategies more effectively and understand their customer base.

## Dataset Description

- **File:** `Customers.csv`
- **Attributes:**
  - `CustomerID`: Unique identifier for each customer
  - `Gender`: Gender of the customer (Male/Female)
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Annual income of the customer in thousands of dollars
  - `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature
- **Size:** 200 entries, 5 columns

## Approach & Methods

1. **Data Exploration & Cleaning:**
   - Checked for missing values and data types
   - Explored distributions of age, income, and spending score
   - Visualized gender distribution and relationships between features
2. **Exploratory Data Analysis (EDA):**
   - Used histograms, pairplots, and heatmaps to understand feature relationships
   - Visualized feature distributions and correlations
3. **Clustering:**
   - Applied K-Means clustering on selected features (Annual Income and Spending Score)
   - Used the Elbow Method to determine the optimal number of clusters
   - Visualized the resulting clusters and centroids

## How to Run

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd CustomerSegmentation
   ```
2. **Install dependencies:**
   - Recommended: Use Anaconda or a virtual environment
   - Required Python packages:
     - pandas
     - numpy
     - matplotlib
     - seaborn
     - scikit-learn
     - dabl (for advanced EDA)
     - missingno (for missing value visualization)
   - Install with pip:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn dabl missingno
     ```
3. **Run the analysis:**
   - Open `Customer Segmentation Analysis.ipynb` in Jupyter Notebook or VSCode
   - Run all cells to reproduce the analysis and visualizations

## Results & Visualizations

- **Distribution Plots:** Age, Annual Income, and Spending Score
- **Gender Distribution:** Pie chart of male vs female customers
- **Pairplots & Heatmaps:** Feature relationships and correlations
- **Cluster Visualization:**
  - Scatter plots showing customer clusters based on income and spending score
  - Centroids of each cluster highlighted
- **Key Insights:**
  - Customers can be grouped into distinct segments based on their spending habits and income
  - These segments can be targeted with tailored marketing strategies

## Requirements

- Python 3.7+
- Jupyter Notebook or compatible IDE
- See the "How to Run" section for required packages

## Credits

- Dataset: [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Analysis and notebook by [Your Name]

---

Feel free to use, modify, and contribute to this project!
