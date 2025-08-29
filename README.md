# Azure-Day-29-Virtual-Network-Project
Project Overview

This project delivers a secure Azure Virtual Network (VNet) infrastructure with multiple subnets and Network Security Groups (NSGs). 
It demonstrates how to control network traffic flow, enforce least-privilege rules and apply segmentation best practices in Azure.

Virtual Network
* Name: MyVNet
* Address Space: 10.0.0.0/16
* Region: UK South

Architecture Implemented
* Virtual Network
* Name: MyVNet
* Address Space: 10.0.0.0/16
* Region: UK South

Subnet Configuration
* WebTier → 10.0.1.0/24 → Web servers and front-end applications
* DatabaseTier → 10.0.2.0/24 → Database servers and back-end services

Network Security Groups (NSGs)
* WebTier-NSG → Protects web-facing resources
* DatabaseTier-NSG → Protects the database subnet

Security Rules
* Allow inbound HTTP (80) and HTTPS (443) traffic to WebTier
* Deny all inbound by default; explicit allow rules only
* Each NSG correctly associated with its subnet

Skills Demonstrated
* Azure Virtual Network design and deployment
* Subnet segmentation for layered security
* NSG configuration and rule management
* Inbound/outbound traffic flow control
* Azure Resource Group organization
* Applying network security best practices

Learning Outcomes
* Azure networking fundamentals in practice
* Network segmentation as a security strategy
* NSG policy creation and association
* Azure Resource Manager deployment workflows
* Understanding of traffic flow enforcement in cloud networks

Project Status
* Day: 29 of 100 Days of Cloud Deployment
* Status: Complete
