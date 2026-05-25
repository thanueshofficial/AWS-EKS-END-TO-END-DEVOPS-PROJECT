# AWS EKS End-to-End Deployment

## Overview
This project demonstrates deploying containerized applications on Amazon EKS using Kubernetes with secure AWS integration and scalable networking configurations.

---

## Technologies Used
- AWS EKS
- Kubernetes
- Docker
- kubectl
- eksctl
- AWS CLI
- Linux

---

## Key Implementations
- Created and configured Amazon EKS cluster
- Configured IAM users, OIDC provider, and IAM Roles for Service Accounts (IRSA)
- Prepared VPC networking, subnets, route tables, and security groups
- Deployed applications using Kubernetes Deployment, Service, and Ingress manifests
- Configured AWS ALB Ingress Controller for external application access
- Performed deployment validation and Kubernetes troubleshooting

---

## Project Workflow
1. Configured AWS CLI and kubectl  
2. Created EKS Cluster using eksctl  
3. Configured Networking and Security Groups  
4. Deployed Kubernetes Workloads  
5. Configured ALB Ingress Access  
6. Validated Application Deployment  

---

## Learning Outcome
- Kubernetes orchestration on AWS
- EKS networking and security
- Kubernetes ingress and traffic routing
- IAM integration with Kubernetes
- Production-style deployment workflow
