# Azure Identity Security and Access Governance Lab

## Project Overview

This project is a practical identity security lab focused on **Microsoft Entra ID**, formerly known as Azure Active Directory.

The goal is to design and document a secure identity and access management environment using users, groups, Multi-Factor Authentication, Conditional Access, role-based access control, and access governance concepts.

This project is aligned with roles related to:

- Cloud Security
- Identity & Access Management
- Authentication
- User Management
- Access Management
- Conditional Access
- Privileged Access
- Cloud Governance
- Cloud Compliance
- Technical Documentation

---

## Why This Project Matters

Identity is one of the most important security layers in modern cloud environments.

Many organizations use Microsoft Entra ID to manage users, groups, authentication, application access, and privileged access.

Weak identity controls can lead to account compromise, privilege abuse, and unauthorized access to company resources.

This lab demonstrates how identity security can be improved using MFA, Conditional Access, role-based access control, and access governance.

---

## Project Goals

- Create a small Microsoft Entra ID identity model.
- Design users and groups for different job roles.
- Document authentication and authorization concepts.
- Configure MFA as a security control.
- Design Conditional Access policies.
- Document privileged access management.
- Explain access reviews and governance.
- Build a professional portfolio project for Cloud Security and IAM roles.

---

## Target Architecture

```text
Microsoft Entra ID Tenant

├── Users
│   ├── developer.user
│   ├── security.auditor
│   └── admin.user
│
├── Groups
│   ├── Developers
│   ├── Security Auditors
│   └── Cloud Administrators
│
├── Security Controls
│   ├── Multi-Factor Authentication
│   ├── Conditional Access
│   ├── Role-Based Access Control
│   └── Access Reviews
│
├── Privileged Access
│   ├── Admin role assignment
│   ├── Just-in-time access concept
│   └── Privileged Identity Management concept
│
└── Documentation
    ├── Identity design
    ├── Security controls
    ├── Conditional Access policy
    └── Access governance model
