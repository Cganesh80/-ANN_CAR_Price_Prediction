# -ANN_CAR_Price_Prediction

About Dataset
Title: “Car Sales Price Prediction Using ANN” Introduction: Problem Statement
As a vehicle salesperson, the main objective is to estimate the overall amount that consumers would spend on buying a new vehicle. The main Objective of this model is to predict the net amount that a customer would likely spend.

Model
We create a model that can estimate the overall amount that consumers would spend given the following characteristics: customer name, customer email, country, gender, age, annual salary, credit card debt, and net worth. We can use Machine Learning or Deep Learning Techniques, here we are using ANN for prediction. Here we are actually predicting using some random values, after that we are predicting using the training dataset. After that we are implementing and predicting using linear Regression and Ridge Regression. Then finally we are comparing the predicted amount with the actual amount.

Algorithm
Neural Network is a series of algorithms that are trying to mimic the human brain and find the relationship between the sets of data. It is being used in various use-cases like in regression, classification, Image Recognition and many more.

As we have talked above, if neural networks try to mimic the human brain then there might be the difference as well as the similarity between them. Let us talk briefly about it.
Some major differences between them are biological neural network does parallel processing whereas the Artificial neural network does series processing also in the former one processing is slower (in millisecond) while in the latter one processing is faster (in a nanosecond).

A neural network has many layers and each layer performs a specific function, and as the complexity of the model increases, the number of layers also increases that why it is known as the multi-layer perceptron.

The purest form of a neural network has three layers input layer, the hidden layer, and the output layer. The input layer picks up the input signals and transfers them to the next layer and finally, the output layer gives the final prediction and these neural networks have to be trained with some training data as well like machine learning algorithms before providing a particular problem.

Working of ANN

At First, information is feed into the input layer which then transfers it to the hidden layers, and interconnection between these two layers assign weights to each input randomly at the initial point. And then bias is added to each input neuron and after this, the weighted sum which is a combination of weights and bias is passed through the activation function. Activation Function has the responsibility of which node to fire for feature extraction and finally output is calculated. This whole process is known as Forward Propagation. After getting the output model to compare it with the original output the error is known and finally, weights are updated in backward propagation to reduce the error and this process continues for a certain number of epochs (iteration). Finally, model weights get updated and prediction is done.

**Dataset Description **

The dataset was downloaded from Kaggle website. The website link is given below.it is about “Car Sales Price Prediction”. It includes five hundred rows and nine columns. It contains numeric, categorical and character. The five hundred rows consists of the data collected from five hundred people. The nine columns encompass various attributes for collecting the data. The nine attributes are customer name, customer email, country, gender, age, annual salary, credit card debt, net worth, car purchase amount.

Customer name-

The customer name includes the name of the customer. It contains the first name and last name of the customer. It is a character data set. It includes the names of the five hundred customers who are approaching the vehicle salesperson for getting the required information for buying a car.

Customer email-

This data set includes the Email address of the customer. It is the personal identifiable information of the customer. It is a varchar data set.

**Country- **

The country data set gives the information about which country the customer belongs to. It is a character data set .We got data from more than two hundred countries.

Gender–

This data set is a categorical (string) dataset. It includes the gender of the customer. It's given 1 for male and 0 for female. There are two hundred and fifty three males and two forty seven females.

Age-

It is a numerical data set which includes the age of the customer.

**salary- **

Different income ways is been plotted like basic pay, benefits, total pay etc….

Credit card debt-

Generally, credit card debt refers to the accumulated outstanding balances that many borrowers carry over from month to month. It is also a float data set.

Net worth-

It is a person, business, or household's whole wealth, including all financial assets and obligations. Here it represents the net worth of a customer. It is also a floating data type.

Car purchase amount-

This data set includes the amount a customer is affordable for buying a car. Again it is also a float data type.