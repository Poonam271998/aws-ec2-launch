# aws-ec2-launch

# AWS EC2 Instance Launch Project

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Cloud](https://img.shields.io/badge/Cloud-Compute-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## Project Overview

This project demonstrates the **step-by-step process of launching an EC2 instance in AWS using the AWS Management Console**.

Amazon EC2 (Elastic Compute Cloud) is a web service that provides scalable computing capacity in the cloud, allowing users to run virtual servers.

---

## Objectives

The main objectives of this project are:

- Understand Amazon EC2 service
- Launch a virtual server in AWS
- Configure instance settings
- Connect to the instance securely

---

## Prerequisites

Before performing this project ensure the following:

- AWS Account
- Access to AWS Management Console
- Basic understanding of cloud computing
- Proper IAM permissions to launch EC2 instances

---

## Architecture

```
User
  │
  ▼
AWS Management Console
  │
  ▼
EC2 Service
  │
  ▼
EC2 Instance
  │
  ▼
Application / Server
```

---

## Steps to Launch EC2 Instance

### Step 1: Login to AWS Console

1. Open AWS Management Console
2. Enter login credentials
3. Click **Sign In**

---

### Step 2: Open EC2 Service

1. In the AWS search bar type **EC2**
2. Click **EC2**
3. EC2 dashboard will open

---

### Step 3: Launch Instance

1. Click **Launch Instance**
2. Enter instance details

---

### Step 4: Configure Instance Name

Example:

```
my-ec2-instance
```

---

### Step 5: Choose Amazon Machine Image (AMI)

Select the operating system for the instance.

Example:

```
Amazon Linux 2
```

---

### Step 6: Choose Instance Type

Select instance size based on requirements.

Example:

```
t2.micro
```

(This is eligible for AWS Free Tier)

---

### Step 7: Configure Key Pair

Create or select a key pair for secure access.

Example:

```
my-keypair.pem
```

This key will be used to connect to the instance.

---

### Step 8: Configure Security Group

Allow required traffic.

Example rules:

```
SSH   TCP   Port 22   Source: Anywhere
HTTP  TCP   Port 80   Source: Anywhere
```

---

### Step 9: Configure Storage

Example configuration:

```
8 GB General Purpose SSD (gp2)
```

---

### Step 10: Launch Instance

Click **Launch Instance**.

The EC2 instance will be created and start running.

---

## EC2 Key Concepts

### EC2 Instance
A virtual server running in AWS cloud.

### AMI (Amazon Machine Image)
A template used to launch EC2 instances.

### Key Pair
Used to securely connect to EC2 instances.

### Security Group
Acts as a virtual firewall controlling inbound and outbound traffic.

---

## Benefits of EC2

- Scalable compute resources
- Pay-as-you-go pricing
- High availability
- Flexible instance configurations

---

## Use Cases

Amazon EC2 is commonly used for:

- Web hosting
- Application servers
- Development and testing environments
- Big data processing

---

## Repository Structure

```
aws-ec2-launch
│
├── README.md
└── project-documentation
```

---

## Author

Poonam Langote

---

## Project Status

Completed
