
# Host a Static Website on Amazon S3 using Terraform

## Project Overview

This project demonstrates how to deploy a static website on Amazon S3 using Terraform, an Infrastructure as Code (IaC) tool. Instead of manually creating and configuring AWS resources, Terraform automates the entire deployment process through code.

The website is hosted on an Amazon S3 bucket configured for static website hosting and made publicly accessible through bucket policies.

---

## Project Objective

- Create an Amazon S3 bucket using Terraform
- Enable static website hosting
- Upload a custom HTML webpage
- Configure public access permissions
- Deploy infrastructure using Infrastructure as Code (IaC)

---

## Architecture

```text
Terraform
    │
    ▼
Amazon S3 Bucket
    │
    ▼
Static Website Hosting Enabled
    │
    ▼
Public Website URL
```

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Terraform | Infrastructure as Code (IaC) |
| AWS S3 | Static website hosting |
| Git & GitHub | Version control and repository management |
| HTML/CSS | Website design |

---

## Project Structure

```text
terraform-s3-website/
│
├── main.tf
├── variables.tf
├── index.html
├── README.md
├── .gitignore
└── terraform.tfstate
```

---

## Terraform Resources Created

### S3 Bucket

Creates an Amazon S3 bucket to host the website.

### Website Configuration

Enables static website hosting and configures the index page.

### Bucket Policy

Allows public read access to website files.

### S3 Object

Uploads the HTML file to the bucket.

---

## Deployment Steps

### 1. Clone Repository

```bash
git clone <repository-url>
cd terraform-s3-website
```

### 2. Initialize Terraform

```bash
terraform init
```

### 3. Validate Configuration

```bash
terraform validate
```

### 4. Preview Changes

```bash
terraform plan
```

### 5. Deploy Infrastructure

```bash
terraform apply
```

Type:

```text
yes
```

### 6. Access Website

```bash
terraform output
```

Open the generated website URL in a browser.

---

## Website Features

- Hosted on Amazon S3
- Publicly accessible
- Created using Infrastructure as Code
- Automated deployment using Terraform
- Custom HTML landing page

---

## Sample Webpage

The deployed webpage displays:

- Project Title
- Developer Name: Manjusri Kalapala
- AWS S3 Hosting Information
- Terraform Deployment Information

---

## Learning Outcomes

Through this project, I learned:

- AWS S3 Static Website Hosting
- Terraform Configuration Files
- Bucket Policies and Permissions
- Infrastructure as Code (IaC)
- Git and GitHub Version Control
- Automated Cloud Resource Deployment

---

## Commands Used

```bash
terraform init
terraform validate
terraform plan
terraform apply
terraform output
terraform destroy
```

---

## Future Enhancements

- Custom Domain Integration
- HTTPS using AWS CloudFront
- CI/CD Pipeline using GitHub Actions
- Responsive Multi-Page Website

---

## Author

**Manjusri Kalapala**  
Advanced App Engineering Analyst

---

## Conclusion

This project successfully demonstrates the deployment of a static website on Amazon S3 using Terraform. It highlights the practical implementation of Infrastructure as Code (IaC) principles by automating cloud resource provisioning and website deployment on AWS.
=======
# terraform-s3-website---project-2
