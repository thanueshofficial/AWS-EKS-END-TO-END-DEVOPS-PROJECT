# AWS EKS End-to-End Deployment Project

## Overview

This project demonstrates the end-to-end deployment of containerized applications on Amazon EKS using Kubernetes.  
The implementation covers AWS infrastructure setup, Kubernetes cluster provisioning, networking configuration, ingress management, IAM integration, and application deployment in a production-style environment.

---

# Technologies Used

- AWS EKS
- Kubernetes
- Docker
- eksctl
- kubectl
- AWS CLI
- IAM
- Application Load Balancer (ALB)
- Linux (Ubuntu)

---

# Project Workflow

## 1. AWS Environment Configuration

Configured AWS CLI on Ubuntu Linux and authenticated using IAM user credentials.  
Installed and configured kubectl for Kubernetes cluster management.  
Verified AWS access and Kubernetes connectivity before cluster provisioning.

---

## 2. EKS Cluster Provisioning

Provisioned Amazon EKS cluster using eksctl.  
Created worker nodes and configured Kubernetes control plane integration.  
Validated cluster creation and verified node status using kubectl commands.

---

## 3. Networking & Security Configuration

Configured VPC networking components including public and private subnet communication.  
Managed Security Groups and IAM permissions for secure cluster access.  
Configured OIDC provider and implemented IAM Roles for Service Accounts (IRSA) to securely integrate Kubernetes workloads with AWS services.

---

## 4. Kubernetes Application Deployment

Containerized applications and deployed them to EKS using Kubernetes manifests.  
Created Deployment, Service, and Ingress YAML configurations for workload management and application exposure.  
Managed pod deployments, service discovery, and internal traffic routing within the Kubernetes cluster.

---

## 5. ALB Ingress Controller Integration

Installed and configured AWS ALB Ingress Controller for external application access.  
Configured Kubernetes Ingress resources to route incoming traffic through AWS Application Load Balancer.  
Validated public accessibility and verified traffic routing to Kubernetes services.

---

## 6. Monitoring & Validation

Monitored Kubernetes resources using kubectl commands.  
Performed deployment validation, troubleshooting, and application testing.  
Verified pod health, ingress configuration, and cluster resource status throughout the deployment process.

---

# Key Learnings

- Amazon EKS cluster provisioning and management
- Kubernetes deployments and service orchestration
- Kubernetes ingress and traffic routing
- AWS networking and security integration
- IAM Roles for Service Accounts (IRSA)
- Production-style Kubernetes deployment workflow
- Kubernetes troubleshooting and validation
