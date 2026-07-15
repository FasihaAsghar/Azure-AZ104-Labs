# Lab 01 - Manage Microsoft Entra ID Identities

## Lab Overview

In this lab, I explored the basics of Microsoft Entra ID by creating and managing user identities in Azure. I created an internal user account, invited an external guest user, created a security group, and assigned users to the group. This lab helped me understand how identity and access management works in Microsoft Azure.

---

## Objectives

- Understand Microsoft Entra ID and Azure tenants.
- Create and configure internal user accounts.
- Invite external guest users.
- Create a Security Group.
- Assign users to the group.
- Learn the difference between internal and guest users.

---

## Prerequisites

- Microsoft Azure Subscription
- Access to Azure Portal
- Microsoft Entra ID

---

## Task 1 - Create and Configure a User

I created a new Microsoft Entra ID user named **az104-user1**. During the user creation process, I configured the user's department, job title, usage location, and enabled the account. Azure automatically generated a temporary password for the user.

**Configuration**

| Setting | Value |
|----------|-------|
| User Name | az104-user1 |
| Department | IT |
| Job Title | IT Lab Administrator |
| Usage Location | United States |
| Account Status | Enabled |

### Screenshot
<img width="949" height="421" alt="image" src="https://github.com/user-attachments/assets/ddce15fb-488d-4888-a974-abd1b31f9fa4" />


---

## Task 2 - Invite an External Guest User

I invited an external user by providing an email address. The invitation email was sent successfully, and the guest account appeared in Microsoft Entra ID.

### Screenshot

<img width="949" height="421" alt="image" src="https://github.com/user-attachments/assets/6ccf5935-8f5f-4669-be54-1e50c3610013" />


---

## Task 3 - Create a Security Group

I created a Security Group named **IT Lab Administrators**. The group uses **Assigned Membership**, allowing administrators to manually manage group members. I also assigned myself as the group owner.

### Group Configuration

| Setting | Value |
|----------|-------|
| Group Type | Security |
| Group Name | IT Lab Administrators |
| Membership Type | Assigned |

### Screenshot

<img width="939" height="454" alt="image" src="https://github.com/user-attachments/assets/f0b9cc2a-3ccd-4371-b0e5-4184d1ae57e8" />

---

## Task 4 - Add Members to the Group

I added both the internal user (**az104-user1**) and the invited guest user to the **IT Lab Administrators** security group. After adding the members, I verified that they appeared successfully in the group's member list.

### Screenshot

<img width="945" height="498" alt="image" src="https://github.com/user-attachments/assets/1adc6f0a-605e-45e9-a4a9-58666b3c7130" />


---

## What I Learned

From this lab, I learned:

- How Microsoft Entra ID manages identities in Azure.
- The difference between internal users and guest users.
- How Security Groups simplify access management.
- How assigned group membership works.
- The importance of Microsoft Entra ID for authentication and authorization.

---

## Reference

This lab was completed by following the Microsoft Learn AZ-104 training material.

**Source:** [https://learn.microsoft.com/training/](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_01-Manage_Entra_ID_Identities.html#lab-introduction)

This documentation contains my own implementation, screenshots, and explanations based on the Microsoft Learn lab.
