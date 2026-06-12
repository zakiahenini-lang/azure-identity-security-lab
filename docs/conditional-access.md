# Conditional Access Policy Design

## Purpose

This document describes the Conditional Access design for the Azure Identity Security and Access Governance Lab.

Conditional Access helps protect access to cloud resources by enforcing security requirements based on user identity, group membership, application, location, device state, and risk signals.

---

## Policy Goal

The main goal of this lab policy is to protect privileged access.

Privileged users such as cloud administrators should be required to complete Multi-Factor Authentication before accessing sensitive cloud management portals.

---

## Example Conditional Access Policy

### Policy Name

```text
Require MFA for Cloud Administrators