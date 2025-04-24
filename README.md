# Customer Segmentation and Purchase Pattern Analysis
Objective
Analyze customer behavior through both segmentation (using clustering) and purchase pattern analysis (using association rules) to derive meaningful business insights.

Dataset Requirements
- Download the "Online Retail" dataset from UCI Machine Learning Repository or a similar e-commerce dataset from Kaggle

- Dataset should contain:

  - Customer information for clustering

  - Transaction/purchase information for association rule mining

Tasks and Mark Distribution
1. Data Preprocessing (2 marks)

   - Load and clean the dataset

   - Handle missing values and duplicates

   - Perform outlier detection and removal

   - Feature scaling/normalization

   - Create relevant features for both clustering and association analysis

2. Customer Segmentation using Clustering (5 marks)

   - Apply Elbow method to determine optimal number of clusters (1 mark)

   - Implement three clustering algorithms:

     - K-means clustering (1.5 marks)

     - Hierarchical clustering (1.5 marks)

     - DBSCAN (1 mark)

   - Calculate and compare Silhouette coefficients for each method

3. Purchase Pattern Analysis using Association Rules (5 marks)

   - Prepare transaction data for association rule mining

   - Define support and confidence thresholds

   - Apply Apriori algorithm to discover frequent itemsets

   - Generate and analyze association rules

   - Compare rules based on different metrics (support, confidence, lift)

   - Provide business insights from discovered rules

