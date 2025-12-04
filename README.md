# 🚀 AWS Cloud Infrastructure Project – End-to-End Deployment & Scalability

This project demonstrates the complete setup of a secure, scalable, and highly available cloud infrastructure on :contentReference[oaicite:0]{index=0}. It covers networking, compute, load balancing, auto scaling, cost monitoring, and professional architecture design using industry best practices. The main objective of this project is to simulate a real-world production-ready environment capable of handling high traffic.

---

## ✅ Task 1: Networking & Subnetting (VPC Setup)

A custom virtual network was created using :contentReference[oaicite:1]{index=1} with two public and two private subnets distributed across multiple Availability Zones for high availability. An Internet Gateway was attached to allow internet access for public subnets. A NAT Gateway was configured to provide secure outbound internet access for private subnets. This setup ensures proper security, traffic isolation, and scalability.

---

## ✅ Task 2: EC2 Static Website Hosting

A Free Tier instance was launched using :contentReference[oaicite:2]{index=2} inside the public subnet. The Nginx web server was installed and used to host a static resume website. Security Groups were configured to allow only HTTP (port 80) and SSH (port 22) access. The website was successfully accessed using the public IP with basic infrastructure hardening applied.

---

## ✅ Task 3: High Availability & Auto Scaling Architecture

High availability was achieved by moving the EC2 instances into private subnets and placing an Internet-facing :contentReference[oaicite:3]{index=3} in public subnets. An Auto Scaling Group was attached to automatically manage EC2 instances across multiple Availability Zones. This architecture ensures automatic load distribution, fault tolerance, and uninterrupted application availability during traffic spikes.

---

## ✅ Task 4: Billing & Free Tier Cost Monitoring

Billing protection was configured using :contentReference[oaicite:4]{index=4} with a ₹100 billing alarm. Free Tier usage alerts were enabled to monitor service limits. This helps prevent unexpected charges and teaches effective cost management for beginners using cloud platforms.

---

## ✅ Task 5: Highly Scalable AWS Architecture Design (10,000 Users)

A professional multi-tier architecture was designed using an Application Load Balancer, Auto Scaling Group, private EC2 instances, and a scalable database layer using :contentReference[oaicite:5]{index=5} with Multi-AZ support. ElastiCache (Redis) was added for caching to improve performance. Security components such as Security Groups, NACLs, and AWS WAF were included. Monitoring and logging were enabled using CloudWatch and logging services. The complete design was documented using a professional draw.io architecture diagram.

---

## 🎯 Project Outcomes

- Gained practical experience with AWS networking and compute services  
- Built a real-world highly available and scalable cloud architecture  
- Learned Auto Scaling and Load Balancing concepts  
- Implemented AWS security best practices  
- Enabled real-time cost monitoring and billing protection  
- Designed enterprise-level AWS architecture for 10,000+ users  

---

✅ This project represents a complete beginner-to-advanced AWS infrastructure implementation suitable for real production-level workloads.
