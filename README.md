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
 **Evidence:**

📷 [View Group Management Screenshot](02-Groups-IAM-Lab-Users.png)

### 3. Licensing

Reviewed Microsoft 365 licensing and license assignment workflows.

**Lab activities:**
- Reviewed available licensing information
- Examined user license assignment status
- Identified Microsoft 365 licensing requirements for identity features
  **Evidence:**

📷 [View Licensing Review Screenshot](03-Licensing-Review.png)

### 4. Multi-Factor Authentication

Configured Microsoft Authenticator as an authentication method for the IAM lab group.

**Lab activities:**
- Configured Microsoft Authenticator
- Targeted the `IAM-Lab-Users` group
- Registered a test user for Microsoft Authenticator
- Verified MFA authentication during sign-in
  **Evidence:**

📷 [View MFA / Microsoft Authenticator Screenshot](05-MFA-User-Registration.png)

### 5. Self-Service Password Reset (SSPR)

Configured Self-Service Password Reset for the IAM lab group.

**Lab activities:**
- Enabled SSPR for `IAM-Lab-Users`
- Reviewed authentication method requirements
- Verified password reset/security information configuration
  **Evidence:**

📷 [View SSPR Configuration Screenshot](06-SSPR-Configuration.png)

### 6. Conditional Access

Created a Conditional Access policy to require MFA for the IAM lab environment.

**Lab activities:**
- Created an MFA Conditional Access policy
- Targeted the IAM lab users
- Reviewed target resources and access controls
- Used report-only mode during initial testing
  
**Evidence:**

📷 [View Conditional Access Screenshot](./07-Conditional-Access-Require-MFA.png)
  
  

### 7. External Collaboration

Reviewed Microsoft Entra external collaboration and guest access settings.

**Lab activities:**
- Reviewed guest user access restrictions
- Reviewed guest invitation settings
- Reviewed external user self-service settings
- Reviewed cross-tenant collaboration controls
  **Evidence:**

📷 [View External Collaboration Screenshot](./08-External-Collaboration-Settings.png)

## Skills Demonstrated

- Microsoft Entra ID user and group administration
- Identity lifecycle and account administration
- Microsoft Authenticator and MFA
- Self-Service Password Reset (SSPR)
- Conditional Access policy configuration
- Guest access and external collaboration settings
- Microsoft 365 licensing awareness
- Identity and access management fundamentals
- Identity governance concepts
- Documentation and troubleshooting

## Project 2 — Identity Governance

This project focuses on Microsoft Entra identity governance capabilities used to manage access, review permissions, and control privileged access.

### 1. Access Reviews

Reviewed Microsoft Entra Access Reviews and the role they play in periodically validating user access to applications, groups, and resources.

**Lab activities:**

- Reviewed the Microsoft Entra Access Reviews feature
- Examined access review configuration and review concepts
- Reviewed how organizations can periodically validate user access
- Identified the role of access reviews in maintaining least-privilege access

**Lab status:** Reviewed / training

### 2. Entitlement Management and Access Packages

Reviewed Microsoft Entra Entitlement Management and Access Packages for managing controlled access to organizational resources.

**Lab activities:**

- Reviewed Access Packages and entitlement management concepts
- Examined how access packages can bundle resources for users
- Reviewed access request and approval concepts
- Studied how entitlement management supports lifecycle-based access

**Lab status:** Reviewed / training

### 3. Privileged Identity Management (PIM)

Explored Microsoft Entra Privileged Identity Management and Just-In-Time privileged access concepts.

**Lab activities:**

- Reviewed Microsoft Entra PIM
- Examined eligible versus active role assignments
- Reviewed Just-In-Time privileged access concepts
- Explored Microsoft Entra role management
- Reviewed PIM auditing and activation concepts

**Lab status:** Hands-on exploration / licensing limited

### Identity Governance Learning Outcome

These exercises provided practical exposure to the principles of least privilege, periodic access review, entitlement management, and Just-In-Time administrative access.

> Note: Some Identity Governance capabilities require Microsoft Entra ID Governance or Microsoft Entra ID P2 licensing. Where the lab tenant did not provide access to a feature, the capability was reviewed through Microsoft documentation and portal exploration rather than represented as a completed configuration.
 
## Professional Development & Certification Preparation

This portfolio is part of an ongoing professional development plan focused on Microsoft identity, access management, and modern cloud administration.

### Current Focus

- Microsoft SC-300: Identity and Access Administrator
- Microsoft Entra ID administration
- Identity and access management (IAM)
- Authentication and MFA
- Conditional Access
- Self-Service Password Reset (SSPR)
- Identity governance and least-privilege concepts
- Microsoft 365 administration
- Endpoint and device management with Microsoft Intune

### Hands-On Development

The lab environment is used to reinforce Microsoft identity concepts through practical configuration, troubleshooting, documentation, and scenario-based exercises.

Additional Microsoft identity and endpoint training is being completed through Microsoft Learn, hands-on labs, and structured certification preparation.

### Career Direction

Targeting opportunities involving:

- Microsoft Entra ID / IAM administration
- Identity and Access Management support
- Microsoft 365 administration
- Endpoint administration
- Cloud and infrastructure support
