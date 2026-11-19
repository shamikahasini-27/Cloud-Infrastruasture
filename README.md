# Cloud-Infrastruasture
# Cloud-Based Centralized Logging and Distributed Application Monitoring Platform

## 📌 Project Overview

This project develops a cloud-based platform to collect and manage logs from multiple applications in one centralized location. It helps administrators identify errors, monitor application health, and view basic performance information through a single dashboard.

## 🎯 Problem Statement

- Application logs are scattered across multiple servers.
- Checking applications individually takes time.
- Identifying errors and failures is difficult.
- No centralized view of application health.

## 💡 Proposed Solution

A centralized monitoring platform that collects, stores, and displays application logs and basic monitoring information through a web dashboard.

## ✨ Key Features

- Centralized application log collection.
- Log searching and filtering.
- Basic performance monitoring.
- Error and failure notifications.
- Single dashboard for application monitoring.

## ☁️ AWS Services Used

| Service | Purpose |
|---|---|
| Amazon EC2 | Hosts sample applications. |
| Amazon CloudWatch | Collects and monitors logs and metrics. |
| Amazon S3 | Stores centralized log files. |
| AWS IAM | Manages resource access. |

## ⚙️ System Workflow

1. Applications run on AWS EC2 instances.
2. Logs are generated and collected using CloudWatch.
3. Log files are stored in Amazon S3.
4. The web dashboard displays logs and monitoring information.
5. Notifications highlight important errors and failures.

## 🛠️ Technologies Used

- Amazon Web Services (AWS)
- Amazon EC2
- Amazon CloudWatch
- Amazon S3
- AWS IAM
- Web Technologies



## 🎯 Expected Outcome

A functional prototype for centralized log management and distributed application monitoring that simplifies troubleshooting and improves application visibility.

---


