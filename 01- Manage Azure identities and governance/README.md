# Module 01: Manage Azure Identities and Governance
## Lab 1.1: Microsoft Entra ID Users, Guest User, Groups, Role Assignment & SSPR Configuration
### Lab Objective
Hands-on configuration of Microsoft Entra ID identity and governance features, including internal users, an external guest user, security groups, role assignment, and Self-Service Password Reset (SSPR).

### Tasks performed
**User Creation**
* Created **2 internal cloud users** in Microsoft Entra ID and **invited 1 external guest** user using B2B collaboration
  
  <img width="919" height="115" alt="image" src="https://github.com/user-attachments/assets/f25d65c3-8633-4857-a6b0-e7cf578bd198" />
  
  <img width="868" height="37" alt="image" src="https://github.com/user-attachments/assets/bf92f4bd-fd59-4a7e-bb45-1d4752d64b60" />
  
  **Group Management**
* Created a **Security Group** to manage users and access centrally. Added users to the group as required.
 
  <img width="1075" height="87" alt="image" src="https://github.com/user-attachments/assets/8e0cf490-3bb5-43ed-af55-c9294940fffe" />

**SSPR Configuration**
* Configured Self-Service Password Reset (SSPR).
* Assigned the Security Group to control which users can use SSPR

## Lab 1.2: Management Group and Resource Group Setup
### Lab Objective
Creating Management Groups and Resource Groups to easily manage Azure subscriptions and resources.

### Tasks performed
**Management Group Setup**
* Created management group as **Rishi_cloud_owner** to manage my subscription
<img width="947" height="171" alt="image" src="https://github.com/user-attachments/assets/6c3f7969-429a-4729-9855-db2b6a7dacff" />

**Resource group setup**
* Created a resource group as **RG_rishi_lab** after selecting my subscription (Azure for student) and Azure region.
<img width="1107" height="100" alt="image" src="https://github.com/user-attachments/assets/b46e8fa0-381d-442c-8bb6-ef4f760c1758" />


### Key Takeaways & Learnings
* Learned how to create and manage internal and external identities in Microsoft Entra ID.
* Understood the difference between Member and Guest users
* Configured SSPR using a Security Group-based scope.
* Understood how groups can be used to simplify identity and access management.
* Configured management group and resource group to understood how we can manage our subscription and resources.

  


