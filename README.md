# Customer Segmentation Analysis

## Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques, specifically K-Means clustering. The goal is to analyze customer data from a mall to identify distinct groups of customers based on their demographic and behavioral attributes. These insights can help businesses target marketing strategies more effectively and understand their customer base.

<img width="780" height="380" alt="image" src="https://github.com/user-attachments/assets/cdf1da87-ab6e-41c9-bbb5-0168148fd87c" />

## Dataset Description

- **File:** `Customers.csv`
- **Attributes:**
  - `CustomerID`: Unique identifier for each customer
  - `Gender`: Gender of the customer (Male/Female)
  - `Age`: Age of the customer
  - `Annual Income (k$)`: Annual income of the customer in thousands of dollars
  - `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and purchasing data
- **Size:** 200 entries, 5 columns

## Approach & Methods

1. **Data Exploration & Cleaning:**
   - Inspected data types, missing values, and summary statistics
   - Explored feature distributions and relationships
2. **Exploratory Data Analysis (EDA):**
   - Visualized distributions of Age, Income, and Spending Score
   - Used pairplots and scatter plots to explore feature relationships
3. **Clustering Analysis:**
   - **2D Clustering:**
     - Clustered customers based on Age & Spending Score, and Annual Income & Spending Score
     - Used the Elbow Method to determine optimal cluster count
     - Visualized clusters and centroids
   - **3D Clustering:**
     - Clustered using Age, Annual Income, and Spending Score
     - Visualized clusters in 3D using Plotly for interactive exploration
   - **Saving Results:**
     - Cluster labels were added to the dataset and saved as `segmented_customers.csv`

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
     - plotly (for 3D visualization)
   - Install with pip:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn plotly
     ```
3. **Run the analysis:**
   - Open `kmeans_clustering_for_customer_data.ipynb` in Jupyter Notebook or VSCode
   - Run all cells to reproduce the analysis, visualizations, and output files

## Results & Visualizations

- **Distribution Plots:** Age, Annual Income, and Spending Score
- **Pairplots & Scatter Plots:** Feature relationships and gender-based analysis
- **2D Cluster Visualizations:**
  - Age vs Spending Score
  - Annual Income vs Spending Score
- **3D Cluster Visualization:**
  - Interactive 3D plot of clusters based on Age, Income, and Spending Score (using Plotly)
- **Key Insights:**
  - Multiple distinct customer segments identified
  - 2D and 3D clustering provide deeper insights for targeted marketing
  - Segmentation results saved for further business use

## Output

- **Segmented Customers File:**
  - `segmented_customers.csv` contains the original data with an added `cluster` column indicating the assigned segment for each customer.

## Requirements

- Python 3.7+
- Jupyter Notebook or compatible IDE
- See the "How to Run" section for required packages

## Credits

- Dataset: [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Analysis and notebook by **Adarsh Shukla**


