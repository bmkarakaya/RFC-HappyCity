# RFC-HappyCity
--------------
Our dataset is a data set where individuals rate the city they live in on a scale of 1 to 5 based on certain parameters and indicate whether they are happy or not. Despite trying three different machine learning methods, I obtained the best result with Random Forest Classification. I would be delighted to hear your suggestions and improvements. Let me provide some information about the dataset:

* It consists of a total of 143 rows and 7 columns.
* General information about the columns:
+ infoavail = the availability of information about the city services
+ housecost = the cost of housing
+ schoolquality = the overall quality of public schools
+ policetrust = your trust in the local police
+ streetquality = the maintenance of streets and sidewalks
+ events = the availability of social community events
+ happy = decision attribute (D) with values 0 (unhappy) and 1 (happy)

To better understand the relationships between the variables, I used a correlation heatmap, correlation matrix, and OLS regression methods. Afterward, I built my machine learning model. I kept the test size at 20%. Finally, I used the confusion matrix to measure the performance of the model.

The link to the dataset I used:  https://www.kaggle.com/datasets/priyanshusethi/happiness-classification-dataset
