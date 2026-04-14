# ☁️ AWS Cloud Resume Project

[![Deploy Resume to AWS](https://github.com/white840117/aws-cloud-resume/actions/workflows/deploy.yml/badge.svg)](https://github.com/white840117/aws-cloud-resume/actions/workflows/deploy.yml)

A professional, high-availability resume website hosted on **AWS** and powered by a fully automated **DevOps CI/CD pipeline**. This project demonstrates the practical application of cloud architecture and modern development workflows.

🔗 **Live Demo:** [https://johnlo.cloud](https://johnlo.cloud)

---

## 🏗️ Architecture Overview

The system utilizes a **Serverless** architecture designed for scalability, security, and low latency:

* **Storage & Hosting**: **Amazon S3** (Static Website Hosting) for durable object storage.
* **Content Delivery**: **Amazon CloudFront** (CDN) for global distribution and low-latency delivery.
* **DNS Management**: **Amazon Route 53** for domain routing and health checks.
* **Security & Encryption**: **AWS Certificate Manager (ACM)** for SSL/TLS encryption (HTTPS).
* **Automated Deployment**: **GitHub Actions** with **AWS CLI** for a seamless CI/CD pipeline.

---

## 🚀 CI/CD Pipeline Workflow

To ensure a "Code-to-Cloud" experience, I implemented an automated deployment pipeline:
1.  **Code Commit**: Any updates to the `index.html` or CSS are pushed to the `main` branch.
2.  **GitHub Actions Trigger**: The push event triggers the deployment workflow.
3.  **S3 Sync**: The latest files are automatically synchronized to the S3 bucket.
4.  **CloudFront Invalidation**: The workflow automatically clears the CloudFront edge cache, ensuring updates are visible globally in seconds.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3 (Badger Red Theme)
* **Cloud Infrastructure**: Amazon Web Services (AWS)
* **DevOps**: GitHub Actions, YAML, Git
* **Networking**: DNS, CDN, SSL/TLS

---

## 🎓 About the Author

**Yun-Ting (John) Lo**
* **University of Wisconsin–Madison**: Master of Science in Information (MSIS)
* **Professional Background**: Former **Solution Architect** at **HPE** and **Marketing Assistant** at **Microsoft Taiwan**.
* **Focus**: Bridging the gap between technical architecture and strategic project management (TPM).

---
*Last Updated: April 2026*