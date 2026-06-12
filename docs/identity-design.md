# Identity Design

## Purpose

This document explains the identity design used in the Azure Identity Security and Access Governance Lab.

The goal is to demonstrate how users, groups, roles, and access controls can be organized in Microsoft Entra ID.

---

## Identity Model

The lab uses three example identities:

| User | Purpose | Group |
|---|---|---|
| developer.user | Represents a normal technical user | Developers |
| security.auditor | Represents a security review user | Security Auditors |
| admin.user | Represents a privileged administrator | Cloud Administrators |

---

## Group Design

Access is managed through groups instead of assigning permissions directly to individual users.

This makes the environment easier to manage and audit.

### Developers

The Developers group represents users who need standard technical access.

Example responsibilities:

- Work with cloud resources
- Access assigned applications
- No privileged administration by default

### Security Auditors

The Security Auditors group represents users who need visibility into security settings.

Example responsibilities:

- Review identity configuration
- Review access assignments
- Inspect security controls
- No destructive permissions

### Cloud Administrators

The Cloud Administrators group represents privileged users.

Example responsibilities:

- Manage tenant settings
- Configure security policies
- Manage identity and access controls

Because this group is privileged, access should be protected with MFA and Conditional Access.

---

## Authentication Design

Authentication verifies the identity of a user.

In this lab, authentication controls include:

- Username and password
- Multi-Factor Authentication
- Conditional Access for privileged users

---

## Authorization Design

Authorization defines what a user is allowed to do.

In this lab, authorization is based on:

- Group membership
- Role-based access
- Least privilege
- Separation between normal and privileged access

---

## Least Privilege Approach

The lab follows the Principle of Least Privilege.

This means users should only receive the access required for their role.

Examples:

- Developers should not have administrator privileges.
- Security auditors should be able to review settings but not modify critical configurations.
- Administrators should use privileged access only when required.

---

## Design Summary

This identity design demonstrates a basic but realistic access model for a cloud environment.

It shows how Microsoft Entra ID can be used to organize users, groups, authentication controls, authorization, and privileged access.