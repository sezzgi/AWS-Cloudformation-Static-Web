# aws-cloudformation-static-web

Automated deployment of a static website using AWS CloudFormation, demonstrating Infrastructure as Code and cloud architecture skills.

## Project Highlights

✨ Infrastructure as Code with AWS CloudFormation  
✨ Automated EC2 instance deployment  
✨ Web server configuration and deployment  
✨ Security group management  
✨ Bash scripting automation

## Key Features

• Cloud Infrastructure
  - Automated EC2 instance provisioning
  - Security group configuration
  - Latest Amazon Linux 2023 AMI
  - Apache web server setup

• Automation
  - Infrastructure as Code
  - Automated deployment scripts
  - User data configuration
  - Zero-touch provisioning

• Web Deployment
  - Static website hosting
  - Apache web server
  - Public accessibility
  - Custom domain support


## Quick Start

1. **Prerequisites**
   - AWS Account
   - AWS CLI configured
   - Git

2. **Deploy**
   ```bash
   # Clone repository
   git clone https://github.com/[your-repo]/aws-cloudformation-static-web
   cd aws-cloudformation-static-web

   # Deploy using AWS CloudFormation
   aws cloudformation create-stack \
     --stack-name static-web-stack \
     --template-body file://template.yml
   ```

3. **Access**
   - Website will be available at the URL provided in CloudFormation outputs
   - Check AWS Console for deployment status

## Project Structure
```
.
├── template.yml          # CloudFormation template
├── static/              # Website files
│   ├── index.html
│   └── assets/
└── scripts/             # Deployment scripts
```

