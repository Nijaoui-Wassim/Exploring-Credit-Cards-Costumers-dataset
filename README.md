# Exploring-Credit-Cards-Costumers-dataset
Exploring Credit Cards Costumers dataset in order to find insights and patterns
## dataset link: https://www.kaggle.com/sakshigoyal7/credit-card-customers
![alt text](https://github.com/Nijaoui-Wassim/Exploring-Credit-Cards-Costumers-dataset/blob/main/screenshot.png?raw=true)

#### 0. data preprocessing, there are no missing values so we just take care of categorical data using OneHotEncoder from sklearn
#### 1. we start but preforming a clustring technique (Kmeans cluster) by the number of clusters found using the elbow technique
![alt text](https://github.com/Nijaoui-Wassim/Exploring-Credit-Cards-Costumers-dataset/blob/main/elbow.png?raw=true)
#### 2. we preform PCA for dimensinality reduction in order to visualize the results at the end
#### 3. we preform the features scaling after splitting the data using the new created labels from the clustring
#### 4. we train a kernel SVM for classification 
#### 5. we got a 90% accuracy and finally we visualize the results on both the train and the test sets:
![alt text](https://github.com/Nijaoui-Wassim/Exploring-Credit-Cards-Costumers-dataset/blob/main/results.png?raw=true)
