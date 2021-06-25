# Machine Learning Engineer Nanodegree - Udacity

Projects for the Machine Learning Engineer Nanodegree at Udacity.
This course shows how to create, train and deploy machine learning models using AWS services like SageMaker, Lambda, S3, IAM and API Gateway.

Link to the course:

https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t




## Projects

### Sentiment Analysis with Pytorch


A Web App that is able to predict if a movie review sentiment is negative or positive. 
The app pass the review text through a public API created with API Gateway. 
The review is than preprocessed using a Lambda function that converts the text to a numeric numpy array of fixed length. 
Finally, the lambda function acess an LSTM Model in SageMaker that does the predictions (positive or negative).


### Plagiarism Detector

This project uses a SVC classifier to predict if a text was plagiarized or not. Since this is a sklearn model, it's necessary to first build
a training script in order to instantiate a SageMaker Estimator. For the features, we extract some similarity measures between each given
text and the original wikipedia page about the subject. Finally, the model is deployed and scored using a sagemaker endpoint.



