# Azure Identity & RBAC Lab Notes

## Company Environment

**Company Name:** Contoso Manufacturing

---

# User Administration

## Steps Taken to Create Users

1. Opened Microsoft Entra ID in Azure Portal
2. Navigated to Users
3. Clicked **New User**
4. Selected **Create New User**
5. Added username and display name
6. Enabled auto-generated password
7. Created user accounts
8. Updated job title, department, and company information
9. Verified account creation in **All Users**

---

## Users Created

* helpdesk.admin
* cloud.engineer
* billing.manager
* hr.specialist
* intern.user

> Passwords intentionally removed from documentation for security best practices.

---

# Group Administration

## Steps Taken to Create Groups

1. Opened Microsoft Entra ID in Azure Portal
2. Navigated to Groups
3. Clicked **New Group**
4. Selected **Security Group**
5. Added group name and description
6. Selected **Assigned** membership type
7. Added users to appropriate groups
8. Verified group membership
9. Tested removing and re-adding users

---

## Security Groups Created

### Cloud-Admins

Administrators responsible for managing Azure cloud infrastructure and resources.

**Members**

* Cloud Engineer
* Chris Green

---

### HelpDesk-Team

Support staff responsible for assisting users with IT issues and account management.

**Members**

* Help Desk Admin
* Intern User

---

### Finance-Team

Finance department users responsible for billing and financial operations.

**Members**

* Billing Manager

---

### HR-Team

Human Resources staff responsible for employee and organizational management.

**Members**

* HR Specialist

---

### Network-Operations

Network administrators responsible for network connectivity and infrastructure operations.

**Members**

* James Brown

---

# Azure RBAC

## RBAC Role Assignments

| User            | Role                |
| --------------- | ------------------- |
| Cloud Engineer  | Contributor         |
| Help Desk Admin | Reader              |
| Billing Manager | Billing Reader      |
| James Brown     | Network Contributor |

---

## Steps Taken to Configure RBAC

1. Opened Azure Subscriptions
2. Selected the **john-cloud-lab** subscription
3. Navigated to **Access Control (IAM)**
4. Clicked **Add Role Assignment**
5. Selected appropriate Azure role
6. Assigned role to selected user
7. Reviewed role assignments under IAM

---

# Key Concepts Practiced

* Microsoft Entra ID
* Azure RBAC
* Security Groups
* IAM (Identity and Access Management)
* Least Privilege Access
* Subscription-Level Permissions
* Enterprise Identity Management
