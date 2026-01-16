# Final Project Assignment: Secure Employee Portal with Microsoft Identity and Access Management

## Overview

**Objective:**  
The goal of this final project is to design and implement a secure Employee Portal leveraging Microsoft Identity and Access Management (IAM). You will use Microsoft Azure Active Directory (Azure AD) to provision users, control access, enforce security policies, and demonstrate best IAM practices in a realistic enterprise scenario. This exercise prepares you for real-world Microsoft IAM implementations, requiring both technical execution and documentation/presentation to colleagues or stakeholders.

---

## **Project Deliverables**

### 1. **Project Planning & Overview**
   - Describe your intended portal (simple web app, resource dashboard, etc.).
   - Outline user roles and access requirements (e.g. HR, IT Admin, Managers, General Staff).

### 2. **Azure AD Setup**
   - Register for an Azure account (free tier is OK).
   - Document your Azure AD tenant creation.
   - Create user accounts and groups corresponding to the portal’s roles.

### 3. **Application Registration & Integration**
   - Register a web or API application in Azure AD for authentication (use a basic app, template, or MS sample).
   - Implement Azure AD authentication in your app (OpenID Connect & SSO).

### 4. **Role-Based Access Control (RBAC)**
   - Define and configure Azure AD roles for each user category.
   - Assign these roles at the application level and via group membership.

### 5. **Security Policies**
   - Enable and enforce Multi-Factor Authentication (MFA) for users.
   - Create and test at least one Conditional Access policy (e.g., require MFA from off-campus locations, block risky sign-ins).

### 6. **Privileged Identity Management (PIM)**
   - Configure Privileged Identity Management for elevated roles (e.g., IT Admin).
   - Implement time-based or approval-based escalation for privileged access.

### 7. **Identity Protection & Monitoring**
   - Simulate at least one identity risk event (e.g., sign-in from unfamiliar location).
   - Show how Azure AD detects, alerts, or remediates this event.

### 8. **Documentation**
   - Step-by-step writeup for each technical step, including screenshots, explanations, and reasons for choices made.
   - Provide a summary of challenges faced and how you resolved them.

### 9. **Presentation**
   - Prepare a 10–15 minute presentation summarizing your project, key IAM concepts, and lessons learned.
   - Use illustrative diagrams (identity flows, access policies, etc.) and demo your portal, if possible.

---

## **Evaluation Criteria**

| Component                  | Description                                                        | Points |
|----------------------------|--------------------------------------------------------------------|--------|
| Planning & Overview        | Clear outline of the project and user access needs                 |   10   |
| Azure AD Setup             | Accurate, complete Azure AD and user/group provisioning            |   10   |
| App Registration           | Proper integration of app with Azure AD authentication             |   15   |
| RBAC Implementation        | Appropriate role/group management and permissions                  |   10   |
| Security Policies          | Effective use of MFA and Conditional Access                        |   15   |
| Privileged Identity Mgmt   | PIM configuration with sample use case                             |   10   |
| Threat Simulation & Logs   | Evidence of risk scenario and monitoring                           |   10   |
| Documentation              | Clear, thorough, and well-organized writeup with visuals           |   10   |
| Presentation               | Engaging, informative, and well-structured summary presentation    |   10   |
| **Total**                  |                                                                    | **100**|

---

## **Recommended Resources**

### **Microsoft Official Docs & Learning**
- [Azure AD Documentation](https://learn.microsoft.com/en-us/azure/active-directory/)
- [Identity and Access Management Fundamentals](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/)
- [Microsoft Learn: Secure your Microsoft 365 enterprise](https://learn.microsoft.com/en-us/training/paths/secure-your-microsoft-365-enterprise/)

### **Hands-On Labs**
- [Microsoft Learn: Protect your identities by using Azure AD](https://learn.microsoft.com/en-us/training/modules/protect-identities-azure-ad/)
- [Quickstart: Add app roles in your application and receive them in the token](https://learn.microsoft.com/en-us/azure/active-directory/develop/quickstart-app-roles-dotnet-core)

### **Application Samples**
- [Azure Active Directory code samples (MS Docs)](https://learn.microsoft.com/en-us/azure/active-directory/develop/sample-v2-code)
- [Microsoft Identity Platform – OpenID Connect Sample](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect)

### **Videos & Tutorials**
- [Microsoft Mechanics – Azure AD Deep Dive Playlist](https://www.youtube.com/playlist?list=PLXtHYVsvn_b-UxbQ3vRQOmoTkCZS6bMnC)
- [Pluralsight: Implementing Security in Azure Solutions](https://www.pluralsight.com/courses/azure-implementing-security)
    - *Free trial available*

### **Community & Support**
- [Stack Overflow: azure-active-directory tag](https://stackoverflow.com/questions/tagged/azure-active-directory)
- [Microsoft Tech Community – Azure AD](https://techcommunity.microsoft.com/t5/azure-active-directory/ct-p/AzureActiveDirectory)

---

## **Notes and Tips**
- The project can use real or dummy users and groups.
- You may use a static or template web app for the portal integration aspect.
- Each technical step should be coupled with your rationale and simplified IAM theory.
- Diagrams (Visio, draw.io, Lucidchart, etc.) are encouraged for illustrating flows and policies.
- If you get stuck, refer first to Microsoft Learn, then the Docs, then community forums.

---

**Deadline:** [Set by instructor or manager]

If you have special requirements, accessibility needs, or further questions, please reach out before starting!
