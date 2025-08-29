# Learn To Deploy Real-Time Website in AWS (NullClass Project)

This repository showcases a complete, hands-on AWS deployment:
- **EC2** for compute
- **RDS (MySQL)** lab: create DB and connect from EC2
- **S3** for static assets
- **CloudFront** CDN in front of S3
- **Auto Scaling Group (ASG) + Application Load Balancer (ALB)**
- **Route 53 + ACM** for custom domain and HTTPS
- **E-commerce app (EverShop) on EC2** with Node.js (and PostgreSQL inside app module)

📄 **Full step-by-step instructions** are included in the attached PDF document in this repo.

---

## Project Snapshot
- **Course:** Learn To Deploy Real Time Website in AWS  
- **Overall Progress:** 100%  
- **Tasks Completed:** 6 / 6

### Modules (Completed)
- ✅ Create an **RDS MySQL** database & connect from EC2 (MySQL CLI)
- ✅ Deploy **E-commerce (EverShop)** on EC2 (Node.js, PostgreSQL), public access
- ✅ Implement **S3** for product images & serve from bucket
- ✅ Configure **Auto Scaling** (ASG) & **ALB**
- ✅ Configure **Route 53** + **ACM** for custom domain & HTTPS
- ✅ Integrate **CloudFront** with S3 and restrict direct S3 access

---

## What You’ll Learn
- Building a **scalable, highly available** web stack on AWS
- Securing apps with **HTTPS** and custom domains
- Optimizing static delivery with **CDN (CloudFront)**
- Operational basics: **PM2**, **NGINX** (optional), and security groups

---

## How to Use This Repo
1. **Open the PDF** in this repository for complete, copy-pasteable steps.
2. Follow modules in order (RDS/EC2 → App → S3 → ASG/ALB → Route53/ACM → CloudFront).
3. Use the **README** as an overview; the **PDF** has the detailed commands and screenshots.

---

## Prerequisites
- Active **AWS account**
- Basic knowledge of VPC, EC2, Security Groups
- SSH key pair for EC2
- Domain name (for Route 53 + ACM module)

---

## Repo Info
- **Suggested Name:** `aws-realtime-website`
- **Short Description:** End-to-end AWS project with EC2, RDS, S3, CloudFront, ASG/ALB, Route 53/ACM, and an e-commerce app.

---

## Notes
- The **RDS module** uses **MySQL** (lab).
- The **EverShop app** uses **PostgreSQL** internally (as per app requirements).  
  These are separate learning modules within the same project.
