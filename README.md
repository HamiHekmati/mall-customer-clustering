<p align="center">
  <img src="https://img.freepik.com/free-vector/shopping-mall-outside-composition-mall-building-with-tags-headlines-shops-wall_1284-58788.jpg?semt=ais_hybrid&w=740" alt="Shopping Mall Illustration" width="650">
</p>

### Mall Customers Segmentation with K-Means and DBSCAN

This project presents a complete workflow for segmenting mall customers using unsupervised clustering techniques. The analysis applies both K-Means and DBSCAN algorithms to identify distinct groups of shoppers based on annual income and spending score, offering actionable insights for targeted marketing and customer engagement strategies.

### Getting Started

To run this project on your own machine, begin by cloning or downloading the repository. Ensure that Python 3.12.3 (or a compatible Python 3.x version) is installed, then install all required dependencies using the included [requirements.txt](https://github.com/HamiHekmati/mall-customer-clustering/blob/main/requirements.txt) file with the command: <pre> ``` pip install -r requirements.txt ``` </pre> Once your environment is ready, open the Jupyter notebook file [Mall_Customers_Clustering.ipynb](https://github.com/HamiHekmati/mall-customer-clustering/blob/main/mall-customer-clustering.ipynb) in Jupyter Notebook, JupyterLab, or upload it to Google Colab for a cloud-based workflow. Make sure the dataset file is available at the path referenced in the notebook, and adjust the file path if necessary to match its actual location on your device. Run all notebook cells in sequence to walk through the full analysis, from data exploration and feature selection to clustering, visualization, and interpretation of customer segments. This setup enables you to fully reproduce the analysis, explore the methodology, and experiment with your own modifications.

### Overview

Segmenting customers is essential for understanding shopper diversity and optimizing business strategies in retail environments. This project uses the Mall Customers dataset to explore how unsupervised learning can reveal natural groupings within a customer base. The workflow covers data exploration, feature selection, clustering, and business interpretation, providing a clear path from raw data to actionable recommendations.

### Dataset

The dataset used in this project is sourced from Kaggle’s [Mall Customers Dataset](https://www.kaggle.com/datasets/kondapuramshivani/mall-customerscsv/data) and includes 200 individual shoppers. Each entry contains the customer’s gender, age, annual income (in thousands of dollars), and a spending score assigned by the mall (ranging from 1 to 100). These features offer a foundation for exploring both demographic and behavioral patterns among mall customers.

### Project Workflow

The workflow begins with data loading, inspection, and visualization to understand the structure and key characteristics of the dataset. Annual income and spending score are selected and standardized as primary features for clustering. The Elbow Method is used to determine the optimal number of clusters for K-Means, and results are visualized using both static and interactive plots. DBSCAN is also applied, with a k-distance graph guiding parameter selection and additional plots illustrating detected clusters and outliers. Cluster centers and summary tables are used to interpret the resulting customer segments, and practical business recommendations are drawn from these insights.

### Key Features & Techniques

This project features end-to-end exploratory data analysis, robust feature selection, and application of two major clustering algorithms—K-Means and DBSCAN. Both static and interactive visualizations are used to examine distributions, relationships, and cluster assignments. The analysis compares the strengths of K-Means (for clear, spherical clusters) and DBSCAN (for identifying noise and non-spherical groups), providing a well-rounded perspective on customer segmentation.

### Results

The analysis revealed several clear customer segments, including high-income high-spending groups, low-income budget-conscious shoppers, and intermediate clusters. Both clustering methods highlighted patterns useful for business action, with DBSCAN additionally identifying outlier customers. These insights form the basis for targeted marketing, personalized offers, and improved customer engagement strategies.

### Limitations and Future Work

A key limitation of the project is the small sample size and limited number of features. Future improvements could include integrating more detailed behavioral data, such as shopping frequency or product preferences, and applying additional clustering or predictive modeling techniques to further refine customer segmentation.

### Contact

For questions, suggestions, or collaboration, please connect via [LinkedIn](https://www.linkedin.com/in/hami-hekmati-399932154/) or by opening an issue in this repository. This project was developed by Hami Hekmati as part of a data science portfolio to demonstrate skills in clustering, exploratory data analysis, and business analytics.
