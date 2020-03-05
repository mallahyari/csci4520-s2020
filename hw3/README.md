# Logistic Regression using SGD [100 points]

In this assignment you will be predicting income from census data using logistic regression. Specifically, you will predict the probability that a person earns more than $50k per year.

For this assignment, you are using **scikit-learn** library. Therefore, you must use the `SGDClassifier` model. The data file that you use for training and test is `adult.data`, it is from the Adult dataset, and is included in the GitHub repository of the homework.

[http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html](http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html)

For this assignment, you will do the following tasks:

### Train Your Model

Split the data into 80% training set and 20% test set. Train your model! You should use logistic regression with L2 regularization.

### Accuracy

Once you trained your model you are going to know how well you are doing. Calculate your accuracy on the test dataset. Also, show the confusion matrix.


### Extract Better Features

Take a look at the raw data in `adult.data`. Right now your model is considering all the features. Good feature extraction is often the key to making good machine learning models. Change the number of features to help improve your model's performance. This is very open ended, be creative and find features that work well with your model.


### Tune Your Submission

Tune your algorithm to train your final model. You should change your feature extraction and training code to produce the best model you can. Try different learning rates and regularization parameters, how do they compare? Also, it is good to start with a high learning rate and decrease it over time, feel free to make use of this learning rate in your `SGDClassifier` algorithm. Include a couple of plots showing the effect of applying different learning rate and regularization parameter. In addition, plot the data along with the **decision boundary** based on your final model.

Your grade for this section will be based on your performance relative to an untuned baseline and to the other other students in class. Good luck!

### Submitting

Submit your python file to the class DropBox on Folio.



