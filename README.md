[![Build Status](https://travis-ci.org/SaschaRodekamp/reKognition.svg?branch=master)](https://travis-ci.org/SaschaRodekamp/reKognition)

# Image Rekognition

Using 'Amazon reKognition' to get insights from images:
 [Amazon Rekognition](https://aws.amazon.com/de/rekognition/)

## Preconditions
To start the application, you need first an AWS account, then install and configure the AWS CLI. 
Your AWS credentials are stored in ```~/.aws```.
[AWS Configuration](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

## Build and Run application

To build and run the project use the Spring-Boot gradle task:
```
./gradlew bootRun
```

Access ```http://localhost:8080``` with your browser.
