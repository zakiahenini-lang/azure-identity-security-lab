# Architecture Overview

## Purpose

This document describes the architecture of the Azure Identity Security and Access Governance Lab.

The lab is designed to demonstrate how Microsoft Entra ID can be used to manage identities, groups, authentication controls, privileged access, and access governance.

---

## High-Level Architecture

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
├── Authentication Controls
│   ├── Multi-Factor Authentication
│   └── Conditional Access
│
├── Authorization Controls
│   ├── Group-Based Access
│   ├── Role-Based Access Control
│   └── Privileged Access
│
└── Governance Controls
    ├── Access Reviews
    ├── Privileged Role Review
    └── Group Membership Review