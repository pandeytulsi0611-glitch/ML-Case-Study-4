# ML Case Study 4: E-Commerce Customer Segmentation

## Project Overview
This project focuses on segmenting e-commerce customers using Machine Learning clustering algorithms. The objective is to identify customer groups based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis.

## Dataset
- **Dataset:** `online_retail_clean.csv`
- **Source:** Mathew K Analytics
- **Records:** 391,150
- **Features:** 9

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithms
1. **K-Means Clustering** – Groups customers into clusters based on purchasing behavior.
2. **DBSCAN** – Identifies density-based customer clusters and potential outliers.
3. **PCA (Principal Component Analysis)** – Reduces dimensions for visualization.

## Project Workflow
1. Data loading and exploration
2. RFM feature analysis
3. Data preprocessing
4. Feature scaling using StandardScaler
5. Customer segmentation using K-Means
6. Customer segmentation using DBSCAN
7. Dimensionality reduction using PCA
8. Cluster visualization and analysis

## Repository Structure
```text
ML-Case-Study-4/
│
├── CaseStudy_4.ipynb
└── README.md
```

## Objective
To understand customer purchasing patterns and discover meaningful customer segments that can help businesses improve marketing strategies, customer retention, and targeted promotions.

## Future Improvements
- Compare clustering performance using evaluation metrics.
- Explore additional clustering algorithms.
- Develop business recommendations for each customer segment.
