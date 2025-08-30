<img width="1700" height="460" alt="github-header-banner" src="https://github.com/user-attachments/assets/288c8ba6-a9b4-4d1f-b16a-8da262b83407" />

## About Me
I am a Cloud Engineer from **Barbados**, driven to craft secure, scalable and cost-effective solutions using AWS technologies. My core strength lies in designing cloud architectures that strike a balance between performance, resilience, and maintainability.

I approach cloud engineering with a security-first mindset and a deep appreciation for strategic planning and thoughtful design. My goal is to contribute to innovative projects that challenge convention and advance the possibilities of cloud computing.

I thrive in collaborative spaces where curiosity fuels innovation and learning never stops. For me, cloud engineering is not just about technology; it's about building systems that help people and ideas thrive. The most effective solutions combine technical skill with clear vision, intentional execution, and a constant drive to improve.

---

## Technical Expertise
I leverage a broad range of AWS services to design secure, scalable and automated cloud solutions:
- **Compute & Serverless**: EC2, Lambda  
- **Networking & API Management**: VPC, API Gateway  
- **Security & Monitoring**: IAM, Cognito, GuardDuty, CloudTrail, CloudWatch, Secrets Manager  
- **CI/CD & DevOps**: CodePipeline, CodeBuild, CodeDeploy, CodeArtifact  
- **Infrastructure as Code**: CloudFormation  
- **Data & Analytics**: DynamoDB, Athena, QuickSight  
- **Storage**: S3

## Other Technologies 
Docker, Linux, Git, GitHub
---

## Selected Projects
### Secure AWS VPC Architecture
Designed a secure and scalable AWS Virtual Private Cloud (VPC) architecture to support sensitive workloads with strong isolation, encrypted communication and layered network security.

**Core components:**
- Custom VPC manually deployed in us-east-1 with CIDR 10.1.0.0/16
- Public and private subnets for workload separation
- Multi-layered traffic control using Network ACLs and Security Groups
- VPC Peering between NovaGrid-1 and NovaGrid-2 for private inter-VPC communication
- Private S3 access via Gateway Endpoint with restrictive bucket policies
- Real-time traffic monitoring using VPC Flow Logs and CloudWatch Log Insights
- Secure admin access via EC2 Instance Connect (no open SSH ports)

📄 [View the full project repository](https://github.com/Shanikah-Boyce/Building-a-Virtual-Private-Cloud)

> *Outcome:* Enforced zero-trust access, improved network observability, and enabled scalable multi-environment infrastructure.

### Secure CI/CD Pipeline
Developed a robust CI/CD pipeline for a Java web application to eliminate manual errors and enable secure, zero-downtime deployments.

**Core components:**
- AWS CodePipeline for workflow orchestration  
- AWS CodeBuild for automated build and testing  
- AWS CodeDeploy for seamless deployments  
- AWS CodeArtifact for dependency management  

📄 [View the full project repository](https://github.com/Shanikah-Boyce/Building-an-Automated-CI-CD-Pipeline-with-AWS-for-Java-Web-Applications)

> *Outcome:* Reduced deployment time by 40% and improved release reliability.

### Containerizing a Web Application with Docker and AWS Elastic Beanstalk
Containerized a lightweight web application using Docker and deployed it to AWS Elastic Beanstalk, enabling scalable and repeatable deployment from local development to production.

**Core components:**
- Dockerfile based on the official Nginx image serving a custom HTML page
- Custom image built and tested locally using Docker CLI
- Elastic Beanstalk environment configured with Docker platform
- Application packaged and deployed as a versioned ZIP archive
- Public access enabled via default VPC settings

> Outcome: Delivered a lightweight, scalable web application infrastructure with seamless deployment from local container to cloud-hosted environment.

📄 [View the full project repository](https://github.com/Shanikah-Boyce/Deploying-a-Web-Application-Using-Docker)

### BankerBot: AI-Driven Banking Assistant with Amazon Lex & AWS Lambda
Built a secure, serverless chatbot to streamline banking interactions using Amazon Lex V2 and AWS Lambda. BankerBot handles balance checks, fund transfers, greetings, and fallback responses—via both voice and text.

**Core components:**
- Lex V2 bot with 0.40 confidence threshold for high-accuracy intent matching
- Custom slot type for accountType: "Checking", "Savings", "Credit" (Visa, Mastercard, Amex)
- Context tracking with input/output tags for seamless multi-turn conversations
- AWS Lambda functions for dynamic responses, slot validation, and backend logic
- FallbackIntent for graceful handling of unsupported or ambiguous inputs

📄 [View the full project repository](https://github.com/Shanikah-Boyce/BankerBot-AI-Chatbot-with-Amazon-Lex-AWS-Lambda)

> *Outcome:* Delivered a scalable, secure, and user-friendly chatbot showcasing best practices in conversational AI, serverless architecture and user-centric design.

---

## Currently Learning
- Terraform and CloudFormation for infrastructure as code  

---

## Certifications

- **CompTIA Security+** - *Achieved Jan 2025*  

---

## Let's Connect
I'm always open to networking and collaboration. Feel free to reach out!

👉 [Connect with me on LinkedIn](https://bb.linkedin.com/in/shanikah-boyce)

---

