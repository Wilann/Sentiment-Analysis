# SageMaker Machine Learning

## Project: Sentiment Analysis

### Source 

Project 1 from Udacity's [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t)

### Description

Used AWS SageMaker to create a web app that interacts with a deployed Recurrent Neural Network (RNN) performing sentiment analysis on movie reviews

- Preprocess data
- Creating a word dictionary to keep track of most frequently appearing words
- Transform reviews by padding and truncating to a fixed length
- Upload data to S3
- Built and trained LSTM PyTorch model (containing model artifacts, training code, and inference code)
- Deployed and tested model through an endpoint
- Deployed the model for the web app
- Used the model for the web app by creating an IAM Role, creating a Lambda function, and setting up an API Gateway

### Run

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).
