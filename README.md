# Microsoft Entra ID SAML Single Sign-On Lab

This lab demonstrates how SAML-based single sign-on can be configured in Microsoft Entra ID.

The goal was to create an enterprise application, assign a user, configure SAML authentication, and verify that SSO works.

---

## Tools Used

Microsoft Entra ID (Azure AD)

---

## Lab Steps

1. Created an Enterprise Application using the Microsoft Entra SAML Toolkit.
2. Assigned a user account to the application.
3. Enabled SAML as the authentication method.
4. Configured the required SAML settings:
- Identifier (Entity ID)
- Reply URL
- Sign-on URL
5. Verified that a SAML token could be issued during login.

---

## Screenshots

### Enterprise Application Created
![Figure 1](figure1-enterprise-app-created.png)

### User Selected for Assignment
![Figure 2](figure2-select-user.png)

### User Ready for Assignment
![Figure 3](figure3-user-selected.png)

### User Successfully Assigned
![Figure 4](figure4-user-assigned.png)

### SAML Selected as Authentication Method
![Figure 5](figure5-saml-selected.png)

### Basic SAML Configuration
![Figure 6](figure6-basic-saml-config.png)

### Successful SAML SSO Test
![Figure 7](figure7-sso-test-success.png)

### Token Signing Certificate
![Figure 8](figure8-token-signing-certificate.png)

---

## What This Demonstrates

• Enterprise application configuration
• Identity assignment and access management
• SAML authentication setup
• Single sign-on validation
