# Terraform Leadership Path  
### SecureTheCloud Academy — Infrastructure as Code (IaC)

**Version:** 2025  
**Author:** SecureTheCloud (Ola)

---

## Overview

This repository represents the **Infrastructure domain** of the SecureTheCloud Academy.

Its sole responsibility is to design, provision, and manage **cloud infrastructure using Terraform** across AWS, Azure, and GCP.

This repository intentionally focuses on:

- Infrastructure modeling
- State management
- Modules and reusability
- Multi-cloud provisioning
- Enterprise IaC patterns

Security, secrets, encryption, and identity protection are **deliberately delegated** to Vault and are covered in the companion repository:

👉 **Vault Leadership Path**  
https://github.com/S3curethecloud/vault-leadership-path

This separation mirrors real-world enterprise architecture.

---

## Architectural Philosophy

> Terraform builds the world.  
> Security systems protect the world.

This repository treats Terraform as an **infrastructure constructor**, not a secrets manager.

All sensitive material (credentials, tokens, encryption keys) is assumed to be sourced from **HashiCorp Vault** or equivalent secure systems.

---

## Repository Structure
volume-1-foundations/ → Terraform core concepts
volume-2-terraform-associate → Certification alignment
volume-3-enterprise-labs → Real-world multi-cloud IaC
anki/ → Study reinforcement

text

---

## Who This Repository Is For

- Engineers transitioning into Infrastructure-as-Code
- Cloud engineers seeking Terraform Associate certification
- Security engineers who want infrastructure fluency
- Architects designing scalable cloud foundations

---

## Companion Repository (Required for Security)

This repository **intentionally excludes** secrets management.

For Vault, encryption, identity, and zero-trust workflows, see:

👉 https://github.com/S3curethecloud/vault-leadership-path

Together, these two repositories form a complete **build + protect** model.

---

## Outcome

Completing this repository prepares you to:

- Design infrastructure declaratively
- Collaborate safely using remote state
- Operate Terraform in team environments
- Integrate securely with Vault-based systems
