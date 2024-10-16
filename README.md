# ProfilesApp

ProfilesApp is a serverless web application that demonstrates a modern cloud-based architecture using AWS services. This project follows the [AWS Hands-On Tutorial](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/) and showcases how to build scalable and resilient web applications.

## Features
- **Frontend:** Hosted on **Amazon S3** as a static website
- **API Management:** **Amazon API Gateway** to expose endpoints for RESTful API Management
- **Backend Logic:** **AWS Lambda** functions to handle business logic with serverless computer service
- **Database:** **Amazon DynamoDB** for fast, flexible NoSQL storage

## How It Works
1. Users interact with a web interface hosted on S3
2. API Gateway routes API calls to Lambda functions
3. Lambda functions perform CRUD operations on DynamoDB
4. The web interface displays updated profile data dynamically
