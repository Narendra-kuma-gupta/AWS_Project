AWS Cloud Infrastructure Project – End-to-End Deployment and Scalability

This project demonstrates the complete setup of a secure, scalable, and highly available cloud infrastructure on Amazon Web Services (AWS). It includes networking, compute, load balancing, auto scaling, cost monitoring, and professional architecture design using real-world industry best practices. The main objective of this project is to simulate a production-ready environment capable of handling high traffic.


Task 1: Networking and Subnetting (VPC Setup)

A custom virtual network was created with two public subnets and two private subnets distributed across multiple Availability Zones for high availability. An Internet Gateway was attached to allow internet access for public subnets. A NAT Gateway was configured to provide secure outbound internet access for private subnets. This setup ensures proper security, traffic isolation, and scalability.



Task 2: EC2 Static Website Hosting

A Free Tier EC2 instance was launched inside the public subnet. The Nginx web server was installed and used to host a static resume website. Security Groups were configured to allow only HTTP on port 80 and SSH on port 22 access. The website was successfully accessed using the public IP address with basic infrastructure hardening applied.



Task 3: High Availability and Auto Scaling Architecture

High availability was achieved by moving the EC2 instances into private subnets and placing an Internet-facing Application Load Balancer in public subnets. An Auto Scaling Group was attached to automatically manage EC2 instances across multiple Availability Zones. This architecture ensures automatic load distribution, fault tolerance, and uninterrupted application availability during traffic spikes.



Task 4: Billing and Free Tier Cost Monitoring

Billing protection was configured by setting a CloudWatch billing alarm at ₹100. Free Tier usage alerts were enabled to monitor service limits. This helps prevent unexpected charges and improves cost management for beginners using cloud platforms.



Task 5: Highly Scalable AWS Architecture Design for 10,000 Users

A professional multi-tier architecture was designed using an Application Load Balancer, Auto Scaling Group, private EC2 instances, and a scalable database layer with Multi-AZ support using Amazon RDS or Aurora. ElastiCache with Redis was added for caching to improve performance. Security components such as Security Groups, Network ACLs, and AWS WAF were included. Monitoring and logging were enabled using CloudWatch and log services. The complete design was documented using a professional draw.io architecture diagram.



Project Outcomes

This project provided practical experience with AWS networking and compute services. It helped build a real-world highly available and scalable cloud architecture. Auto Scaling, Load Balancing, and AWS security best practices were implemented. Real-time cost monitoring and billing protection were enabled. This project represents a complete beginner-to-advanced AWS infrastructure implementation suitable for real production-level workloads.

