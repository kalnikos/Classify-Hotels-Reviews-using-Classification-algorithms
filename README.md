# Classify Hotels Reviews using Classification algorithms  
The main concept of the project is to create a model that can predict the type of  review. The data set concerned reviews exported from London Hotels. 
I started the project with a small data set and I realised that the data were unbalanced, I had a big difference between the positive and the negative reviews and just a few neutral comments. The model was able to identify the positive comments, but the main problem was with the negative and neural ones.in order to solve this issue I used a bigger data set which had more negative comments in order to improve the prediction model.
After that, I used an evenly distributed technique to balance the positive and negative reviews, and I chose to focus in these two review categories aiming to develop a model that I could earn over than 90% accuracy.

## Code and Resources Used
Python Version: 3

Packages: pandas, numpy, sklearn, pickle

## Model Building 
Firstly, I created a class which helped me with the review text and the customer rating. After that, I used the vectorizer method to convert the text to numeric type, I splitted the data into train and test, with a test size of 33%. 

I tried 3 different models

•	SVM

•	Decision Trees

•	Logistic Regression

The model that performed better was the SVM. I trained the model and I earned an accuracy over than 98%, certainly I didn't stop and I computed the cross validation scores that showed an overfitting model. In order to overcome this issue I implemented a Grid Search to find a suitable boundary for the C parameter.

Above are the F1 scores of the tree classification models with unbalanced data. 

## Model performance using F1 scores

For the first data set:

•	SVM  P:0.83, N:0.56

•	Decision Trees P:0.80  N:0.29

•	Logistic Regression P:0.83 N:0.56

Using a bigger data set, an evenly distributed distribution in order to balance the positive with the negative reviews and identifying a proper value for the C parameter, the F1 scores were at a satisfactory level.

•	SVM  P:0.90, N:0.91

