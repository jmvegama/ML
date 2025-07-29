# Customer Segmentation with Clustering

This repository contains a Jupyter notebook demonstrating how to perform customer segmentation using classical clustering algorithms. The notebook walks through exploratory data analysis, preprocessing and the application of three popular clustering methods:

- **KMeans**
- **Hierarchical Agglomerative Clustering**
- **DBSCAN**

The goal is to group customers into segments based on their characteristics so that business strategies can be tailored to each group.

## Installation

1. Install **Python 3.10** or later.
2. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn yellowbrick
   ```

## Running the Notebook

1. Place the dataset file `datos_segmentacion_clientes.csv` in the project folder (or adjust the path inside the notebook). This file is not included in the repository and must be obtained separately.
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open **`Clustering.ipynb`** and execute the cells sequentially to reproduce the analysis and clustering models.

## Dataset

The notebook expects a CSV file named `datos_segmentacion_clientes.csv` separated by semicolons (`;`). If you do not already have this dataset, obtain it from the original provider or any similar public source of customer data and place it in the repository directory before running the notebook.
