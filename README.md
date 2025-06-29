# AWS-Project
Aws-Vpc-Subnetting-Auditing-Monitoring-5Tier Architecture

# AWS Architecture Project: VPC – Subnetting – Auditing – Monitoring

## 🌐 Project Overview

This project demonstrates the implementation of a robust cloud infrastructure using Amazon Web Services (AWS). Key components include:

- ✅ Virtual Private Cloud (VPC) with **20 subnets**
- 🛡️ **CloudTrail** for activity auditing
- 📊 **CloudWatch** for real-time monitoring
- 🖥️ Bastion Host for secure access
- 📈 Auto Scaling setup for performance optimization

The infrastructure was designed to ensure **security, scalability, fault tolerance**, and **cost-effectiveness**.

---

## 🧑‍💻 Team Members

- **Deva Yadhala** (Regd No: 21B91A5763)
- **Pydam Naidu Kallempudi** (Regd No: 21B91A5719)
- **Naveen Gochipatha** (Regd No: 21B91A5713)

Guided by **Mr. Aashu Dev**, AWS Certified Solutions Architect

---

## 🏗️ AWS Services Used

- **Amazon VPC** - Custom virtual private cloud setup with subnetting
- **Amazon EC2** - Instances used for bastion host and other services
- **CloudTrail** - Audit all user and API activity
- **CloudWatch** - Monitor and alert on infrastructure health
- **Amazon S3** - Storage for CloudTrail logs
- **Internet Gateway & Route Tables** - For secure routing

---

## 🔧 Implementation Steps

### VPC & Subnetting
- Created a VPC with **CIDR blocks**
- Configured **20 subnets** across Availability Zones
- Setup **Internet Gateway**, **Route Tables**, and **Security Groups**

### EC2 Instances
- Configured 4 EC2 instances (public and private)
- Set up **Bastion Host** in public subnet for SSH access
- Enabled inter-instance connectivity

### CloudTrail
- Created a **Trail** to log events across AWS regions
- Stored logs in an S3 bucket
- Verified system logs

### CloudWatch
- Monitored EC2 instances
- Created custom **alarms** and **metrics**
- Enabled proactive troubleshooting

---

## 🏁 Outcome

This AWS infrastructure provides:

- 🔐 Secure access and auditing
- 📶 High availability with AZ-distributed subnets
- 📉 Real-time monitoring and logging
- ⚙️ Scalable cloud architecture

---

## 📸 Architecture Diagrams

> 📌 Include screenshots of rough and final architecture here (e.g., VPC diagrams, EC2 setup, CloudTrail config, etc.)

---

## 📄 Report

Read the full [project report (PDF)](./AWS_project_report.pdf) for detailed explanations and screenshots of each step.

---

## 📬 Contact

For questions or collaboration, feel free to reach out:

- GitHub: [@DevaYadhala-04](https://github.com/DevaYadhala-04)

---


