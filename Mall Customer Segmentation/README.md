MALL CUSTOMER SEGMENTATION

Customer segmentation (also known as market segmentation) is the division of potential customers in a given market into discrete groups. That division is based on customers having similar enough: Needs, i.e., so that a single whole product can satisfy them and Buying characteristics, i.e., responses to messaging, marketing channels, and sales channels, that a single go-to-market approach can be used to sell to them competitively and economically. 

PROBLEM

To make predictions and find clusters of potential customers' of the mall and thus help Marketing Team to plan the strategy accordingly. Here, we try to understand basic customers' data and find who can be Target Customers' that bring additional revenue to the mall.

DATA
 
![image](https://user-images.githubusercontent.com/73286521/103289426-27576000-4a0d-11eb-8e48-b8f5b5fe2dbd.png)
This is a Kaggle problem. The data contains 5 columns viz., CustomerID, Gender, Age, Annual Income(k$) and Spending Score(1-100). Here, Gender is Categorical whereas rest are Numeric in nature. The dimensions of the data are (200,5). The data doesn't contain any missing values.

DATA PREPROCESSING

Checking null values:
![image](https://user-images.githubusercontent.com/73286521/103289692-ce3bfc00-4a0d-11eb-8895-fc7e4c72907d.png)
We have 0 null values!
After Data Preprocessing, we move on to Data Visualization.

DATA VISUALIZATION

1.Gender Plot:
![image](https://user-images.githubusercontent.com/73286521/103290110-c6c92280-4a0e-11eb-8fad-a078e52ca7a1.png)

2.Age Plot:
![image](https://user-images.githubusercontent.com/73286521/103290144-dfd1d380-4a0e-11eb-89f0-3dc59fcecbe3.png)

3.Age vs Spending Score:
![image](https://user-images.githubusercontent.com/73286521/103290212-fed06580-4a0e-11eb-8bca-5a8d77997c96.png)

4.Annual Income vs Spending Score:
![image](https://user-images.githubusercontent.com/73286521/103290257-1dcef780-4a0f-11eb-8bd8-7936a837fd58.png)

ALGORITHM & MODEL

K-Means Algorithm is used to form clusters of customers' having similar characteristics. K-Means model is used with number of clusters 5 (Using Elbow Method). 
![image](https://user-images.githubusercontent.com/73286521/103290316-48b94b80-4a0f-11eb-8576-4c0061719fad.png)

SOFTWARE USED

The software used is Python. Numpy, Pandas, Matplotlib, Seaborn, Jupyter Notebook are the libraries used for this project.

ANALYSIS

Using K-Means Clustering, 5 clusters were formed based on the customer's Annual Income and Spending Score.
The 5 clusters that were formed were:
![image](https://user-images.githubusercontent.com/73286521/103290434-8d44e700-4a0f-11eb-9c8c-059279f50316.png)

a. High Income, High Spending Score (Cluster 5) - Target these customers by sending new product alerts which would lead to increase in the revenue collected by the mall as they are loyal customers.

b. High Income, Low Spending Score (Cluster 2) - Target these customers by asking the feedback and advertising the product in a better way to convert them into Cluster 5 customers.

c. Average Income, Average Spending Score (Cluster 1) - Can target these set of customers by providing them with Low cost EMI's etc.

d. Low Income, High Spending Score (Cluster 4) - May or may not target these group of customers. Depends on mall.

e. Low Income, Low Spending Score (Cluster 3) - Don't target these customers since they have less income and want to save money
