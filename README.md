# -SparkSQL-and-MLlib-Analyzing-Purchase-Transactions
Big Data 

This project involves an in-depth study of purchase transactions using SparkSQL and MLlib. After generating the data, the analysis encompasses SparkSQL workflows for filtering, grouping, and reporting, followed by MLlib workflows for data preparation, machine learning model training, prediction, and evaluation.

Step 1 – Data Creation:
A program is designed to create two datasets - Customers (C) and Purchases (P) - with various attributes. These datasets simulate real-world purchase transactions with diverse customer characteristics.

Tasks done using SparkSQL Workflows :

Filtered out purchases from P with a total purchase amount above $600, storing the result as T1.

Grouped the purchases in T1 by the number of items purchased. Calculate the median, min, and max of total amounts spent for purchases in each group. Report the results to the client side.

Grouped the purchases in T1 by customer ID for young customers (18-25 years old). Report customer ID, age, total number of items purchased, and total amount spent by each customer. Store the result as T3.

Identified and reported customer pairs (C1 and C2) from T3 based on age, total amount spent, and total item count.

Task done using MLlib Workflows :

Generated a dataset composed of customer ID, transaction ID, age, salary, transaction number of items, and transaction total. Store it as Dataset.

Randomly split the Dataset into Trainset (80%) and Testset (20%).

Trained at least 3 machine learning algorithms to predict TransTotal using age, salary, and TransNumItems as features. Apply the algorithms over Testset.

*Task 2.8:* Use at least 3 metrics for evaluating the algorithms from Task 2.7 using Regression Evaluation.

*Task 2.9:* Reported and discussed the results, comparing the performance of different models in a table and provided insights into their effectiveness and efficiency.This project involves an in-depth study of purchase transactions using SparkSQL and MLlib. After generating the data, the analysis encompasses SparkSQL workflows for filtering, grouping, and reporting, followed by MLlib workflows for data preparation, machine learning model training, prediction, and evaluation. 

Step 1 – Data Creation: A program is designed to create two datasets - Customers (C) and Purchases (P) - with various attributes. These datasets simulate real-world purchase transactions with diverse customer characteristics. Tasks done using SparkSQL Workflows : Filtered out purchases from P with a total purchase amount above $600, storing the result as T1. 
Grouped the purchases in T1 by the number of items purchased. Calculate the median, min, and max of total amounts spent for purchases in each group. 

Report the results to the client side. Grouped the purchases in T1 by customer ID for young customers (18-25 years old). Report customer ID, age, total number of items purchased, and total amount spent by each customer.

Store the result as T3. Identified and reported customer pairs (C1 and C2) from T3 based on age, total amount spent, and total item count. Task done using MLlib Workflows : Generated a dataset composed of customer ID, transaction ID, age, salary, transaction number of items, and transaction total. Store it as Dataset. 

Randomly split the Dataset into Trainset (80%) and Testset (20%). Trained at least 3 machine learning algorithms to predict TransTotal using age, salary, and TransNumItems as features. Apply the algorithms over Testset. 

*Task 2.8:* Use at least 3 metrics for evaluating the algorithms from Task 2.7 using Regression Evaluation. 

*Task 2.9:* Reported and discussed the results, comparing the performance of different models in a table and provided insights into their effectiveness and efficiency.
Skills: Spark SQL · Spark MLib · PySpark · Machine Learning
