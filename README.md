## Serverless Deep Learning Framework</br>

## Introdcution</br>

In this project I have introduced clothes classification service where the user takes the picture of the clothes they want to wear. Then the classifier classifies the images of the clothes to which category they belong to. I have used AWS Lambda, docker and tensorflow-lite for deploying the model. Lambda is a service from AWS which allow us to deploy deep learning models</br></br>

## Objective Serving models with TensorFlow-Lite</br>
- Deploying deep learning models with AWS Lambda</br>
- Exposing the Lambda function as a web service via API Gateway</br></br>

## Problem Statement</br>
Solving cloths classification problem using Serverless Deep Learning. Here we send the picture with the URL to the model that we are going to deploy with AWS Lambda and then the service will reply with different classes in which one this class will be pants and we will also have some score for it.</br></br> 

## Description</br>

Here I have introduced a clothes classification service. Where the user takes the picture of the clothes they want to wear. Then the classifier tells the user the classified classification. Here we use keras and tensorflow for image classification for classifying the pictures of different clothes and AWS Lambda for deploying the model. </br></br> 

### Lambda</br>
Lambda is a service from AWS which allows us to deploy many different machine learning models.</br>

Here we send the picture with the URL to the model that we are going to deploy with AWS Lambda and then the service will reply with different classes in which one this class will be pants and we will also have some score for it.  Here we use tensorflow-lite internally.</br></br>

### Questions Answered</br>
#### What AWS Lambda is and difference between other approaches?</br>
#### What is the tensorflow-lite and why it is better for this particular use case?</br>
To this we will package everything in to a docker container and deploy it to AWS Lambda.  Finally, we will expose this Lambda function as web service API gateway.
Serverless is the concept of removing infrastructure considerations for deploying code. Instead of having to manage servers and infrastructure by ourselves, a serverless service takes care of that for us and only charges according to use.</br></br>

### Output</br>

![image](https://github.com/srsapireddy/Serverless_Deep_Learning_Code/assets/32967087/e54d5697-fe77-4151-b01a-45a7c122afa6)



