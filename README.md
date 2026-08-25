
# ☁️ Cloud Web App Deployment

A simple web application deployed on **AWS EC2** using **Nginx** and **Amazon Linux 2023**.

## 🌐 Live Website

**Live Demo:** http://3.90.10.50

## 📌 Project Overview

This project demonstrates how to deploy a simple HTML web application on an AWS EC2 instance using the Nginx web server.

The application is hosted on an Amazon Linux 2023 EC2 instance and can be accessed through the instance's public IP address.

## 🛠️ Technologies Used

* AWS EC2
* Amazon Linux 2023
* Nginx
* HTML
* Linux

## 🚀 Deployment Steps

1. Created an AWS EC2 instance.
2. Configured the Security Group.
3. Allowed SSH access on port **22**.
4. Allowed HTTP access on port **80**.
5. Connected to the EC2 instance.
6. Installed Nginx.
7. Started and enabled the Nginx service.
8. Created a custom HTML web page.
9. Deployed the application using Nginx.
10. Verified the deployment using `curl`.
11. Accessed the application using the EC2 Public IP address.

## ✅ Application Status

**Deployment completed successfully.**

The web application is running on **AWS EC2** and is served using **Nginx**.

## 📂 Project Structure

```text
cloud-web-app-deployment/
│
├── index.html
├── README.md
└── screenshots/
    ├── nginx-deployment.png
    └── live-website.png
```

> **Note:** The EC2 public IP address may change if the instance is stopped and started again, unless a static Elastic IP is used.

Use this as your final README. It looks professional and strong for GitHub and your project submission.
