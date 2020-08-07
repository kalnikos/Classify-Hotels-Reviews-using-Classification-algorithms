# Reviews
The main concept of the project is to create a model that can predict the type of reviews. The data set concerned reviews exported from some London Hotels. 
I started the project with a small data set and I realised that I had big difference between the positive and the negative reviews and just a few neural comments. The model was able to identify the positive comments, but the main problem was with the negative and neural ones. To solve this issue I used a different, bigger data set which had more negative comments in order to improve the prediction model.
After that, I used an evenly distributed technique to balance the positive and negative reviews, and I chose to focus in these two review categories for my predictions.
In addition, after I made these changes the F1 score of our model had increased at a satisfactory level.


## Code and Resources Used
Python Version: 3

Packages: pandas, numpy, sklearn, pickle

## Model Building 
First, I created a class which helped me with the review text and the customer rating. After that, I used the vectorizer method to convert the text to numeric type, I splitted the data into train and test, with a test size of 33%. 

I tried 3 different models

•	SVM

•	Decision Trees

•	Logistic Regression

## Model performance using F1 score

For the first data set:

•	SVM  P:0.83, N:0.56

•	Decision Trees P:0.80  N:0.29

•	Logistic Regression P:0.83 N:0.56

Using a bigger data set and an evenly distribution in order to balance the positive with the negative reviews, the  using the F1 score got improved.

•	SVM  P:0.92, N:0.93

