# Cloud-Resume-challenge-

The Cloud Resume Challenge is a project that involves building a personal resume website and deploying it using various AWS services. 

Amazon S3 (Simple Storage Service): S3 is used to store and serve the static website files, such as HTML, CSS, and JavaScript. You can upload your website files to S3 buckets, and it provides high availability and scalability for hosting your website.

CloudFront: CloudFront is a content delivery network (CDN) that improves the performance of your website by caching content in edge locations around the world. It is used to distribute the website files globally, reducing latency and improving the overall user experience.

AWS Certificate Manager: AWS Certificate Manager (ACM) provides SSL/TLS certificates for securing your website with HTTPS. It allows you to generate and manage SSL certificates to encrypt the communication between your website and its visitors.

Lambda: AWS Lambda is a serverless computing service that allows you to run your code without provisioning or managing servers. In the Cloud Resume Challenge, Lambda is used to execute Python code to retrieve and store the site visitor count.

API Gateway: API Gateway acts as a gateway for your APIs and allows you to create, publish, and manage APIs for your application. It can be used to expose Lambda functions as HTTP endpoints, enabling communication between the website and Lambda function.

DynamoDB: DynamoDB is a NoSQL database service provided by AWS. In the Cloud Resume Challenge, DynamoDB is used to store and manage the visitor count data retrieved by the Lambda function. It provides fast and scalable performance for read and write operations.

Terraform: Terraform is an infrastructure-as-code tool that allows you to define and provision your AWS infrastructure using declarative configuration files. It helps automate the deployment of AWS resources required for the Cloud Resume Challenge.

HTML, CSS, and JavaScript: These are the fundamental web technologies used to build the website. HTML is used for structuring the content, CSS for styling, and JavaScript for interactive features.

Python: Python is the programming language used in the Lambda function to retrieve and store the site visitor count. It provides a simple and powerful environment for serverless computing.

GitHub repositories: GitHub is a web-based platform for version control and collaboration. It is used to store the source code of the Cloud Resume Challenge project, enabling you to track changes, collaborate with others, and manage your codebase.

GitHub Actions: GitHub Actions is an automation tool that allows you to define workflows to automate various tasks, such as code deployment and running tests. In the Cloud Resume Challenge, it is used to automate the deployment of code and perform testing.

By leveraging these services, tools, and technologies, the Cloud Resume Challenge helps you showcase your skills in building and deploying a scalable and secure web application on the AWS cloud.
