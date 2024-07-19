# Cloud Internship Journal

## Week 1:
### Day 1: May 13, 2024
**Introduction:**
- This day marked the beginning of my internship in the Cloud domain with a focus on AWS.
- The primary objective was to get acquainted with the company, understand the project scope, and start with the basics of AWS services.

### Day 2: May 14, 2024
**Activities and Tasks Completed:**
- **Onboarding:**
  - Completed the company onboarding process which included setting up the necessary tools and software required for remote work.
  - Attended an introductory meeting with the supervisor and team members to understand the project goals and expectations.

### Day 3: May 15, 2024
**AWS Fundamentals:**
- **AWS Account Setup:**
  - Created an AWS account and configured basic settings.
  - Set up Multi-Factor Authentication (MFA) for account security.
- **AWS Management Console:**
  - Navigated through the AWS Management Console to familiarize myself with various services.
- **Basic AWS Services:**
  - Amazon EC2 (Elastic Compute Cloud): Launched and terminated an EC2 instance to understand instance types, AMIs, key pairs, and security groups.
  - Amazon S3 (Simple Storage Service): Created an S3 bucket and performed basic operations like uploading, downloading, and deleting objects.

### Day 4: May 16, 2024
**Learning and Skills Development:**
- Understood the fundamental concepts of cloud computing and its benefits.
- Gained practical experience with the AWS Management Console.
- Learned the basics of managing and deploying resources on AWS.
- Improved understanding of key AWS services like EC2, S3, and RDS.

### Day 5: May 17, 2024
**Tools and Technologies Used:**
- AWS Management Console
- SSH for connecting to EC2 instances
- S3 Browser for managing S3 buckets

## Week 2:
### Day 1: May 27, 2024
**Introduction:**
- The second week of my internship involved completing the "AWS Cloud Practitioner Essentials" course and undertaking a practical task to upload files from a local machine to an EC2 instance.

### Day 2: May 28, 2024
**Activities and Tasks Completed:**
- **AWS Cloud Practitioner Essentials Course:**
  - Gained a comprehensive understanding of AWS services and core concepts through the AWS Cloud Practitioner Essentials course.

### Day 3: May 29, 2024
- Launched a new EC2 instance with Ubuntu.
- Configured security groups to allow SSH access.
- Faced initial issues with SSH configuration and instance connectivity, resolved with supervisor's guidance.

### Day 4: May 30, 2024
- Installed necessary packages (e.g., scp) on the local machine.
- Attempted file transfer using scp, encountered permission issues on the EC2 instance.
- Researched and adjusted file permissions and user roles on the EC2 instance.

### Day 5: May 31, 2024
- Successfully transferred files from the local machine to the EC2 instance using the scp command.
- Verified the successful transfer of files and their integrity on the EC2 instance.
- Documented the process and solutions for future reference.

## Week 3:
### Day 1: Jun 3, 2024
**Create Card Game:**
- Designed the layout of the card game using HTML and CSS.
- Implemented the basic game logic and interactions using JavaScript.
- Tested the game locally to ensure proper functionality and user experience.

### Day 2: Jun 4, 2024
**Deploying the Card Game using AWS CodePipeline:**
- Set up an S3 bucket to host the static files of the card game.
- Configured bucket policies to make the game publicly accessible.
- Uploaded the card game files to the S3 bucket.
- Created a CodePipeline to automate the deployment process.
- Configured the pipeline stages: S3, GitHub link, build (AWS CodeBuild), and deploy S3.
- Set up AWS CodeBuild to package and prepare the game files for deployment.

### Day 3: Jun 5, 2024
**Initial Setup and User Authentication:**
- Set up a new React application with Create React App.
- Integrated AWS Amplify.
- Configured Amazon Cognito for user authentication.

### Day 4: Jun 6, 2024
**Enhancing the React App and Deployment:**
- Added protected routes and a user profile page in the React app.
- Configured Amplify Hosting.
- Deployed the initial version.
- Conducted testing and fixed issues.

### Day 5: Jun 7, 2024
**CI/CD Integration with GitHub:**
- Linked GitHub repository to AWS Amplify for CI/CD.
- Configured build settings and branch-based deployments.
- Verified the CI/CD pipeline.
- Documented the setup process.

## Week 4:
### Day 1: Jun 10, 2024
**Setting Up the Project Repository and IAM Roles:**
- Created a new project repository in AWS CodeCommit.
- Configured Identity and Access Management (IAM) roles and policies for the project.
- Granted necessary permissions for CodeCommit, AWS Amplify, Amazon Cognito, AWS Lambda, Amazon API Gateway, and Amazon DynamoDB.
- Cloned the repository to the local machine and initialized the project structure.

### Day 2: Jun 11, 2024
**Initializing AWS Amplify and Configuring Cognito:**
- Integrated AWS Amplify into the project and configured it for development.
- Set up Amazon Cognito for user authentication.
- Created user pools and identity pools to manage user identities.
- Configured Amplify to use Cognito for sign-up, sign-in, and authentication flows.

### Day 3: Jun 12, 2024
**Implementing Backend Services with AWS Lambda and API Gateway:**
- Created AWS Lambda functions to handle backend logic.
- Defined API endpoints using Amazon API Gateway.
- Integrated Lambda functions with API Gateway to expose the backend services.
- Tested the API endpoints to ensure they are working correctly.

**Setting Up and Configuring Amazon DynamoDB:**
- Created DynamoDB tables to store application data.
- Defined table schemas and configured primary keys.
- Integrated Lambda functions with DynamoDB to perform CRUD operations.
- Tested the integration by performing read and write operations from the Lambda functions.

### Day 5: Jun 14, 2024
**Finalizing the Application and Deployment:**
- Completed the front-end development using React and connected it to the backend services.
- Configured Amplify to deploy the application, including the front-end and backend services.
- Conducted end-to-end testing of the application to ensure all components are working seamlessly.
- Deployed the final version of the application using AWS Amplify and verified its functionality.
