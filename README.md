# 🔐 Azure Identity and Access Management (IAM) Project

This project demonstrates the practical implementation of **Access Management** within an Azure Active Directory (Azure AD) environment. It follows the principles of Zero Trust and least privilege by enforcing robust identity and access controls for users, devices, and resources.

---

## 📌 Objectives

- Implement Role-Based Access Control (RBAC) for structured access control
- Configure Conditional Access Policies to enforce contextual access
- Enable and enforce Multi-Factor Authentication (MFA)
- Define workflows to ensure least privilege access to sensitive resources

---

## 🧠 Skills Demonstrated

- Identity & Access Management (IAM)
- Azure RBAC (Role-Based Access Control)
- Conditional Access Configuration
- Multi-Factor Authentication (MFA)
- Azure AD Security & Compliance
- Zero Trust Security Principles

---

## 🛠️ Tools & Services Used

- **Microsoft Azure Portal**
- **Azure Active Directory**
- **Conditional Access**
- **Microsoft Authenticator (for MFA)**
- **Privileged Identity Management (PIM)**

---

## 🔍 Project Breakdown

### ✅ 1. Role-Based Access Control (RBAC)

- Assigned roles to users based on their job responsibilities:
  - **Admins**: Contributor role 
  - **Developers**: Reader access for monitoring workloads
  - **Custom Role**: Defined a custom role with only deployment and log-read permissions

📌 *RBAC ensures users only have the minimum permissions needed to do their work.*
---
<img src="assets/Screenshot 2025-04-08 at 20.20.29.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.24.34.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.24.46.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.28.35.png" width="300">  <img src="assets/Screenshot 2025-04-08 at 20.41.01.png" width="300">

---

### ✅ 2. Conditional Access Policies

- Created policies to **enforce contextual access** based on:
  - **Device Compliance** (only allow compliant devices)
  - **Location-Based Restrictions** (block access from outside approved countries)

- Policy Actions:
  - **Grant access** only if conditions are met
  - **Require MFA** for all access attempts

📌 *Policies reduce risk from unauthorized devices or risky sign-ins.*
---
<img src="assets/Screenshot 2025-04-08 at 20.41.38.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.15.20.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.42.00.png" width="300">  <img src="assets/Screenshot 2025-04-08 at 20.57.03.png" width="300">


---

### ✅ 3. Multi-Factor Authentication (MFA)

- Enforced MFA for all users using **Azure AD MFA configuration**
- Users enrolled using **Microsoft Authenticator**
- Enabled both **per-user MFA** and **MFA via Conditional Access**

📌 *MFA mitigates risks from compromised credentials.*

---
<img src="assets/Screenshot 2025-04-08 at 20.36.18.png" width="300"> <img src="assets/Screenshot 2025-04-08 at 20.31.53.png" width="300">

---

## 🧾 Summary

This project reflects a real-world implementation of Zero Trust principles in Azure by securing identity and access paths through strong authentication, contextual access, and principle of least privilege.

> ✅ Designed.  
> ✅ Tested.  
> ✅ Documented.  

---

## 📂 Repo Structure

