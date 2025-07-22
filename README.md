# Azure Load Balancer Infrastructure Project

## 🎯 Objective
Create a public Azure Load Balancer that distributes traffic to 2 backend VMs with Azure Bastion, NAT Gateway, and a custom VNet.

## 🔧 Tools Used
- Azure Portal
- Azure Load Balancer (Standard, Public)
- Azure Bastion
- NAT Gateway
- 2 Virtual Machines (Ubuntu)
- Custom VNet with 3 subnets

## 🧱 Architecture
- Load Balancer distributes HTTP traffic to backend pool (VM1, VM2)
- Azure Bastion allows secure VM access
- NAT Gateway allows outbound internet for VMs
- Network Security Groups (NSGs) open port 80



