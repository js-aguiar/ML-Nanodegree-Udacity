# Machine Learning Engineer Nanodegree - Udacity

Projects from the Machine Learning Engineer Nanodegree at Udacity. This course shows how to deploy machine learning models to AWS using services like SageMaker, Lambda, S3, IAM and API Gateway.


Link to the course:

https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t




## Projects

### Sentiment Analysis with Pytorch


A Web App that is able to predict if a movie review sentiment is negative or positive. 
The app pass the review text through a public API created with API Gateway. 
The review is than preprocessed using a Lambda function that converts the text to a numpy array of fixed length. 
Finally, the lambda function acess an LSTM Model in SageMaker that does the predictions.



