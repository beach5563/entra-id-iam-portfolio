# Microsoft Entra ID IAM Portfolio

Hands-on Microsoft Entra ID identity and access management portfolio covering users, groups, MFA, SSPR, Conditional Access, and identity governance concepts.

## Overview

This portfolio documents hands-on identity and access management labs completed using a Microsoft 365 Business Premium lab tenant.

The goal of this project is to build practical experience with Microsoft Entra ID administration, authentication, access controls, and identity governance while preparing for Microsoft identity and access management roles and the SC-300: Microsoft Identity and Access Administrator certification.

The lab environment is used to safely practice identity administration tasks, document configuration steps, and develop troubleshooting and operational knowledge that can be applied to real-world IAM environments.

## Environment

- Microsoft 365 Business Premium lab tenant
- Microsoft Entra ID
- Microsoft Authenticator
- Microsoft Entra Conditional Access
- Self-Service Password Reset (SSPR)
- Microsoft Entra groups and user administration
- Identity governance concepts

## Project 1 — IAM Foundation

This project focuses on foundational Microsoft Entra ID identity and access management tasks performed in the lab tenant.

### 1. User Administration

Created and configured test users to practice basic identity lifecycle and account administration.

**Lab activities:**
- Created test users in Microsoft Entra ID
- Reviewed user profile and account properties
- Verified user type and sign-in identifiers
- Reviewed group memberships and assigned resources
 **Evidence:**

📷 [View User Administration Screenshot](01-Users-Overview.png)

### 2. Group Management

Created a dedicated security group for IAM lab testing.

**Lab activities:**
- Created the `IAM-Lab-Users` security group
- Configured assigned membership
- Added test users to the group
- Verified direct group membership

### 3. Licensing

Reviewed Microsoft 365 licensing and license assignment workflows.

**Lab activities:**
- Reviewed available licensing information
- Examined user license assignment status
- Identified Microsoft 365 licensing requirements for identity features

### 4. Multi-Factor Authentication

Configured Microsoft Authenticator as an authentication method for the IAM lab group.

**Lab activities:**
- Configured Microsoft Authenticator
- Targeted the `IAM-Lab-Users` group
- Registered a test user for Microsoft Authenticator
- Verified MFA authentication during sign-in

### 5. Self-Service Password Reset (SSPR)

Configured Self-Service Password Reset for the IAM lab group.

**Lab activities:**
- Enabled SSPR for `IAM-Lab-Users`
- Reviewed authentication method requirements
- Verified password reset/security information configuration

### 6. Conditional Access

Created a Conditional Access policy to require MFA for the IAM lab environment.

**Lab activities:**
- Created an MFA Conditional Access policy
- Targeted the IAM lab users
- Reviewed target resources and access controls
- Used report-only mode during initial testing

### 7. External Collaboration

Reviewed Microsoft Entra external collaboration and guest access settings.

**Lab activities:**
- Reviewed guest user access restrictions
- Reviewed guest invitation settings
- Reviewed external user self-service settings
- Reviewed cross-tenant collaboration controls
