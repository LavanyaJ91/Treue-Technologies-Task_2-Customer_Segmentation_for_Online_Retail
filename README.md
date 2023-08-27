# Treue-Technologies-Task_2-Customer_Segmentation_for_Online_Retail

INTRODUCTION:

    Customer segmentation is a crucial task for businesses to better understand and target their customer base. In this project, we analyze an online retail dataset and perform customer segmentation based on three key factors: Recency, Frequency, and Monetary value of transactions.

IMPORTING THE LIBRARIES:

    Importing the libraries are NumPy, pandas, matplotlib, Standard Scalar, Kmeans

UPLOADING THE CSV FILE:

    Uploading the CSV file using the pandas library and reading the CSV file
  
    To check the Shape, info, and description of the datasets

PERFORMING EXPLORATORY DATA ANALYSIS:

    To check the null values present in the data sets using isnull().sum()

    Drop all null values using dropna 

    Check the unique values of given datasets
Analyzing the Customers based on 3 factors:

    Recency: Number of days since last purchase
    
    Frequency: Number of transactions
    
    Monetary: Total Number of transactions

    Plot the Amount, Frequency, and Recency using a boxplot
REMOVING OUTLIERS:

     Removing the Outliers for Amount, Frequency, and Recency  using Quantile methods
MODEL CREATING:

      Import the k means cluster classifier, 
      Because this is unscaled data we use k means clusters

      Using the elbow method choosing the k values 

      plot the k values
CONCLUSION:

       1. Customers with Cluster Id 2 are the customers with
       high amount of transactions as compared to other customers.
       
       2. Customers with Cluster Id 2 are frequent buyers.
       
       3. Customers with Cluster Id 0 are not recent buyers and hence 
       least of importance from business point of view.
