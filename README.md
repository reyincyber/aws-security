# Cloud Security (Azure & AWS) Hands-on Projects

## Project 1: [Automating Incident Response - EC2 Instance Isolation with AWS Lambda and GuardDuty](https://github.com/reyincyber/aws-security/tree/76173448fc10cfd4cc84144fd26fd18b737f80d3/automating-incident-response)
🔗 Code and Documentation:
[GitHub Repository](https://github.com/reyincyber/aws-security/tree/861c663e487afa7e966cab4069c6db1d76fa8ace/automating-incident-response); [Medium Walkthrough](https://cyberrey.medium.com/automating-ec2-instance-isolation-with-aws-lambda-and-guardduty-33a34fc88177); [Youtube](https://youtu.be/RCmdjOjsGUw)

This project automates the process of detecting and isolating compromised EC2 instances in real-time, minimizing security risks. It is designed for AWS users of all levels, including beginners, and includes step-by-step instructions to deploy the required resources and configurations. The workflow uses EC2, GuardDuty, S3, EventBridge, and Lambda to detect, mitigate, and notify about security threats while adhering to the **principle of least privilege** for IAM roles and policies.
![image alt](https://github.com/reyincyber/aws/blob/a62ca55ed1a79838400d853ac95882f37a783510/automating-incident-response/architectural%20diagrams/automating_idr_bc.drawio.png)

### Project 2: [AI-Driven Threat Detection in AWS Environments](https://github.com/reyincyber/CloudSecurity--Azure-AWS/blob/main/AI-Driven%20Threat%20Detection%20in%20AWS%20Environments%20.pdf)
With cyberattacks growing more sophisticated and the adoption of cloud services expanding, traditional security methods alone are no longer enough. AWS offers several AI-powered tools designed to enhance security and stay ahead of potential threats. This project provides conceptual and hands-on exploration of AWS's AI/ML-powered security services (GuardDuty, Detective, Macie, Rekognition) focused on improving threat detection, forensic investigation, and sensitive-data discovery across cloud workloads. Includes practical recommendations, architecture considerations, and a sample incident analysis (exposed S3 keys, attacker activity, and remediation guidance).

### Project 3: [AzureDDM Dynamic Data Masking - G6 Open Day](https://github.com/reyincyber/CloudSecurity--Azure-AWS/blob/main/AzureDDM%20Dynamic%20Data%20Masking%20-%20G6%20Open%20Day.pdf)
A hands-on walkthrough demonstrating how to create an Azure SQL Database, configure a user with limited privileges, and enable Dynamic Data Masking (DDM) to obfuscate sensitive columns in query results, useful for protecting PII in development or reporting scenarios while preserving usability for authorized roles.

## License

This collection of projects and documentation is licensed under the MIT License and should be used for Educational Purpose only. See the included [LICENSE](LICENSE) file for full details.
