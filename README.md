# Predicting whether an individual has Diabetes using the Random Forest Classification Model in ML

In this project, I wanted to predict whether a patient would have Diabetes or not according to some given features such as glucose concentartion, diatolic_bp, thickness, bmi etc...

The diabetes feature in the dataset is stated as True and False but I have changed True as 1 and False as 0. Using seaborn countplot, I determined that in the dataset, 268 people were diagnosed with Diabetes and the remaining 500 were not. 

Then using the train_test_split function, I split the data into training and testing data and then finaly used Random Forest Classifictaion for prediction. When I ran the accuracy score, the model had an accuracy score 79.2%. 
