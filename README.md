# customer-segmentation-model
This project aims to perform customer segmentation using K-Means clustering on a dataset of mall customers. Customer segmentation helps businesses understand their customer base better, allowing them to make data-driven decisions for marketing, product development, and customer service.

## DATASET:

The dataset used for this project is named "Mall_Customers.csv." It contains the following columns:
  1. CustomerID: Unique identifier for each customer.
  2. Genre: Gender of the customer.
  3. Age: Age of the customer.
  4. Annual Income (k$): Annual income of the customer.
  5. Spending Score (1-100): A score representing the customer's spending behavior.

## PROJECT OVERVIEW

1. Data Exploration: We load and explore the dataset to gain insights into the customer data.

2. Elbow Method: We use the Elbow Method to determine the optimal number of clusters for K-Means clustering.

3. K-Means Clustering: We perform K-Means clustering on the "Annual Income" and "Spending Score" attributes.

4. Visualizations: We create scatter plots to visualize the clusters and centroids.

## GETTING STARTED

To run this project, you need to have Python installed on your machine. You will also need the following libraries:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

## To replicate the analysis, follow these steps:

1. Clone this repository to your local machine.

2. Download the dataset "Mall_Customers.csv" and place it in the project folder.

3. Run the Jupyter Notebook or Python script to perform the analysis.

Results
The project will generate cluster visualizations and provide insights into the customer segmentation based on annual income and spending score.


```bash
pip install pandas numpy matplotlib seaborn scikit-learn
