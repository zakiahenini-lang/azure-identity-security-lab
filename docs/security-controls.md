# Security Controls

## Purpose

This document describes the security controls used in the Azure Identity Security and Access Governance Lab.

The goal is to show how Microsoft Entra ID can help protect identities, privileged access, and cloud resources.

---

## Multi-Factor Authentication

Multi-Factor Authentication adds an additional verification step during sign-in.

Instead of relying only on a password, users must confirm their identity using another factor, such as:

- Mobile app approval
- One-time passcode
- Security key
- Phone verification

In this lab, MFA is required for privileged users such as cloud administrators.

---

## Conditional Access

Conditional Access allows access decisions to be based on conditions.

Example conditions:

- User group
- Application
- Device state
- Location
- Risk level
- Sign-in behavior

Example lab policy:

```text
If user is in Cloud Administrators group
and user accesses Azure Portal
then require Multi-Factor Authentication.