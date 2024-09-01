# Web_Application_Backend_Infra
Project portfolio for website deployment

This project demonstrates how to deploy a Next.js application using AWS services such as S3, CloudFront, DynamoDB, and bucket policies. The infrastructure is managed using Terraform.

## Table of Contents
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Setup and Deployment](#setup-and-deployment)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Deploying the Infrastructure](#deploying-the-infrastructure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Architecture

The infrastructure for this project is built using the following AWS services:

1. **Amazon S3**: Used to store static files of the Next.js application.
2. **Amazon CloudFront**: Provides a CDN for the static files, enhancing the performance and security of the application.
3. **Amazon DynamoDB**: Used for storing data related to the application.
4. **Terraform**: Used to define and provision the cloud infrastructure.
5. **Bucket Policies**: Used to control access to the S3 buckets.

The architecture ensures that the application is scalable, secure, and highly available.

## Technologies Used

- **Next.js**: A React framework for building server-side rendering and static web applications.
- **AWS S3**: Object storage service that offers industry-leading scalability, data availability, security, and performance.
- **AWS CloudFront**: A fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally.
- **AWS DynamoDB**: A key-value and document database that delivers single-digit millisecond performance at any scale.
- **Terraform**: An open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services.

## Setup and Deployment

### Prerequisites

Ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html)
- [AWS CLI](https://aws.amazon.com/cli/)
- [Node.js and npm](https://nodejs.org/)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/nextjs-portfolio.git
    cd nextjs-portfolio
    ```

2. **Install the dependencies**:
    ```bash
    npm install
    ```

### Deploying the Infrastructure

1. **Configure AWS CLI** with your credentials:
    ```bash
    aws configure
    ```

2. **Initialize Terraform**:
    ```bash
    terraform init
    ```

3. **Apply the Terraform configuration**:
    ```bash
    terraform apply
    ```

    Confirm the apply with `yes`.
