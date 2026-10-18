\# CI/CD Automation Using AWS Lambda



\## Project Overview

This project demonstrates a basic CI/CD deployment workflow using GitHub, AWS CodePipeline, AWS Lambda, and Amazon S3.



\## Objective

To automate the deployment of a simple HTML application whenever changes are pushed to the GitHub repository.



\## AWS Services

\- AWS CodePipeline — automates the pipeline stages.

\- AWS Lambda — runs deployment automation logic.

\- Amazon S3 — stores the deployed website files.

\- Amazon CloudWatch — stores Lambda execution logs.



\## Project Structure

```text

CI-CD-Lambda-Project/

├── app/

│   └── index.html

└── README.md

```



\## Application

The sample HTML page displays a message confirming that the CI/CD project application is running.



\## Planned Workflow

1\. Push application changes to GitHub.

2\. AWS CodePipeline detects the source changes.

3\. AWS Lambda performs the deployment automation step.

4\. The HTML application is uploaded to Amazon S3.

5\. CloudWatch stores execution logs.



\## Current Status

\- GitHub repository created.

\- Sample HTML application uploaded.

\- S3 bucket created.

\- Lambda function created.

\- CodePipeline configuration and end-to-end testing are pending.



\## Repository

https://github.com/Shital-7841/CI-CD-Lambda-Project

