# Customer Onboarding Application Architecture


## Overview

Welcome to the Customer Onboarding Application project! In this project, we aim to build a secure and efficient customer onboarding application hosted on AWS for a banking company. The application will process customer information submitted via the onboarding form, verify it against a third-party driver’s license validation service, and ensure that the customer’s selfie and driver’s license photos match.

## Scenario

You are a cloud application developer working for a banking company. The company has decided to develop and deploy a customer onboarding application on AWS. Given the nature of the business, there will be significant exchange of sensitive information between the banking company and customers, and the system needs to ensure that the information submitted is valid.

### Key Features:
- **Matching Submitted Information**: The information provided in the onboarding application must match the information on the customer’s driver’s license.
- **Selfie and Driver’s License Photo Verification**: The selfie submitted by the customer must match the driver’s license photo.
- **Third-Party Verification**: The data submitted by customers must be validated against a third-party service to ensure its authenticity.

## Goal

The goal of this project is to help the banking company build and deploy a secure and reliable customer onboarding application on AWS.

## Services Used

The solution will involve several AWS services to ensure scalability, security, and reliability:
- **Amazon S3**: To store customer-submitted documents (selfies, driver’s licenses).
- **AWS Lambda**: For serverless processing of the customer information.
- **Amazon Rekognition**: For photo matching and verification between the selfie and driver’s license.
- **Amazon API Gateway**: To provide RESTful APIs for front-end communication with the backend.
- **AWS Identity and Access Management (IAM)**: To manage permissions and roles.
- **DynamoDB**: For storing customer and transaction data.
- **AWS SNS**: For storing requests
- **AWS X-Ray**: For monitoring 

## Setup

**1. Clone the Repository**:
    ```bash
   git clone https://github.com/your-repo/customer-onboarding-aws.git
   ```
**2. Navigate to the project directory**:
    ```bash
   cd customer-onboarding-aws
   ``` 
