# Add New Guest User (Microsoft Entra ID – Control Stack Aligned)

This project simulates the process of adding a B2B guest user to a Microsoft Entra tenant using the Azure portal. The goal is to build operational fluency in external identity onboarding and map the workflow to the seven-layer Entra Control Stack.

## Purpose

Add a guest user to the tenant and trace how the action touches governance layers such as external entry controls, audit visibility, and authority definition. The project focuses on clarity, not complexity, and serves as a baseline for expanding future identity projects.

## Action Summary

- Navigate to Microsoft Entra Admin Center
- Select **New guest user**
- Enter external email and invite
- Confirm directory listing and optional audit trail

## Control Stack Mapping

- **Layer 1 – Authority Definition**: Confirmed admin has permission
- **Layer 2 – Scope Boundaries**: Not used in this action
- **Layer 3 – Test Identity Validation**: Verified guest appears in directory
- **Layer 4 – External Entry Controls**: Core enforcement layer for guest onboarding
- **Layer 5 – Privilege Channels**: Not involved; no role assigned
- **Layer 6 – Device Trust Enforcement**: Not enforced in this simulation
- **Layer 7 – Continuous Verification**: Sign-in logs and access reviews recommended

## Outcome

Guest user was successfully invited and listed as an external identity. No roles or access were granted. Recommended follow-up includes Conditional Access enforcement and periodic access reviews.

This is the first in a short series of small, targeted identity projects. Each maps directly to the Entra Control Stack for consistent operational practice.
