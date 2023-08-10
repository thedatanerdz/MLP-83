# MLP 83
- Deploy fastAPI Text classification model on aws lambda
- Use FASTAPI - swagger uu for api testing and devlopment
- Use Docker for good devops practices

# AWS Lambda with Machine Learning:

AWS Lambda is a serverless compute service. It allows you to run code without provisioning or managing servers. When using it with machine learning, you can deploy your trained machine learning models onto Lambda functions. These functions can be triggered by various events, such as HTTP requests, file uploads, or scheduled tasks.

For example, let's say you've trained a machine learning model to recognize objects in images. You can package that model with your Lambda function and create an API endpoint. When you send an image to the API, Lambda will automatically run the model and return the results, all without you needing to worry about server management.

# Docker:

Docker is a platform that enables you to develop, package, and deploy applications and their dependencies in a consistent and isolated environment called a container. Containers allow you to bundle an application along with all the libraries and settings it needs to run reliably across different computing environments.

Imagine you have an application that uses specific software libraries and configurations. With Docker, you can package your application and its dependencies into a container image. This image can then be easily shared and run on any system that supports Docker, ensuring that your application runs consistently regardless of where it's deployed.

In the context of machine learning, you can use Docker to create containers that encapsulate your machine learning model, its dependencies, and any required scripts. This makes it easier to deploy and manage your machine learning applications across different environments, from development to production.

# Bringing It Together:

Combining AWS Lambda and Docker, you can create Lambda functions that use Docker containers to deploy machine learning models. This enables you to build and deploy serverless machine learning applications that are highly scalable, isolated, and easy to manage. When a Lambda function is triggered, it can pull and run the Docker container with your machine learning model, allowing you to leverage the benefits of both technologies.
