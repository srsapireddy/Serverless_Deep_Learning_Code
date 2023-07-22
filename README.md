## Serverless Deep Learning Framework</br>

## Introdcution</br>

In this project, I introduced a clothes classification service where the user takes a picture of the clothes they want. Then the classifier classifies the images of the clothes to which category they belong. I have used AWS Lambda, docker, and TensorFlow-lite for deploying the model. Lambda is a service from AWS that allow us to deploy deep learning models</br></br>

## Objective Serving models with TensorFlow-Lite</br>
- Deploying deep learning models with AWS Lambda</br>
- Exposing the Lambda function as a web service via API Gateway</br></br>

## Problem Statement</br>
Solving clothes classification problems using Serverless Deep Learning. Here we send the picture with the URL to the model that we will deploy with AWS Lambda, and then the service will reply with different classes in which one this class will be pants, and we will also have some score for it.</br></br> 

## Description</br>

Here I have introduced a clothes classification service. Where the user takes a picture of the clothes they want to wear. Then the classifier tells the user the classified classification. Here we use Keras and TensorFlow for image classification for classifying the pictures of different clothes and AWS Lambda for deploying the model. </br></br> 

### Lambda</br>
Lambda is a service from AWS that allows us to deploy many different machine-learning models.</br>

Here we send the picture with the URL to the model that we will deploy with AWS Lambda, and then the service will reply with different classes in which one this class will be pants, and we will also have some score for it.  Here we use TensorFlow-lite internally.</br></br>

### Questions Answered</br>
#### What is AWS Lambda, and what is the difference between other approaches?</br>
#### What is the TensorFlow-lite, and why is it better for this particular use case?</br>
To this, we will package everything into a docker container and deploy it to AWS Lambda.  Finally, we will expose this Lambda function as a web service API gateway.
Serverless is the concept of removing infrastructure considerations for deploying code. Instead of having to manage servers and infrastructure by ourselves, a serverless service takes care of that for us and only charges according to use.</br></br>

### Presentation Link </br>
https://docs.google.com/presentation/d/1lAVSrXsIDzfN08h1OyyJXevqLpqUOIAA/edit?usp=sharing&ouid=114982669494228087786&rtpof=true&sd=true

### Output</br>

![image](https://github.com/srsapireddy/Serverless_Deep_Learning_Code/assets/32967087/e54d5697-fe77-4151-b01a-45a7c122afa6)



