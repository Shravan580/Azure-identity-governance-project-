# Azure Identity Governance Project
Project Overview
This project demonstrates identity and access management using Microsoft Entra ID and Azure Role-Based Access Control (RBAC).

The environment simulates a company with separate teams for Cloud Administration, Development, and Support Operations.

# Business Scenario
The organization requires controlled access to Azure resources:

Cloud Administrators manage cloud infrastructure.
Developers deploy and maintain applications.
Support Engineers monitor resources and perform operational checks.
Resource Groups
rg-app-prod
rg-infra-prod

# Security Groups
Cloud-Admins
Developers

# RBAC Model
Cloud-Admins → Contributor

Developers → Contributor

# Technologies Used

Microsoft Entra ID
Azure RBAC
Azure Resource Groups
Identity Governance
Security Groups

# Tasks Performed
Created security groups
Created test users
Added users to groups
Created Azure Resource Groups
Assigned RBAC permissions
Verified role inheritance through groups
Reviewed access assignments

# Security Principles Applied

Least Privilege Access
Group-Based Access Management
Centralized Identity Governance
Role-Based Access Control

# Outcome
Successfully configured a group-based access model using Microsoft Entra ID and Azure RBAC to manage permissions across multiple Azure Resource Groups.
