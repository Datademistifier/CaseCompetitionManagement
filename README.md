# CaseCompetitionManagement
Built an application using Agile. Developed a scalable serverless platform using AWS services (S3, CloudFront, Lambda, Cognito) used Dynamodb as Database, to streamline case competition processes.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Note: This project is no longer hosted online. To view or run the platform, follow the instructions below to set it up locally.**

## Features
- User and role management (students, judges, organizers)
- Room and schedule management
- Presentation feedback and scoring
- AWS-based backend with DynamoDB storage

## Getting Started (Local Setup)

### Prerequisites
- **npm**, **Git**, and an **IDE** of your choice.

### Setup
1. Clone the repository:CaseCompetitionManagement

2.Install dependencies:
npm install aws botocore3
3.Set up environment variables in a .env file (API keys, database connection strings, etc.).

4.Run the project locally. Open the app in your browser by navigating to:
http://localhost:3000/website/index.html

5.Key APIs
/createAndGetusers: Create and fetch user details
/getStudent_dashboard_data: Retrieve student dashboard data
/uploadFeedbackForm: Upload feedback forms
