
# 🧠 Deploying Active Directory on Windows Server

This project demonstrates the step-by-step process of deploying Active Directory (AD) within a Windows Server environment. The lab includes setting up a domain controller, creating user accounts, and joining a Windows client to the domain. This project highlights my knowledge in Windows Server administration and Active Directory fundamentals — critical skills for IT support and system administration roles.

---

## 🖼️ Lab Overview (Screenshots + Descriptions)

### 1. Installing Active Directory
![Installing Active Directory](Deploying%20Active%20Directory/1.%20Installing%20Active%20Directory%20.png)

Here, we begin by installing the **Active Directory Domain Services (AD DS)** role on the Windows Server using Server Manager. This is the foundational step to promoting a server to a Domain Controller.

---

### 2. Adding a Domain Controller
![Adding a Domain Controller](Deploying%20Active%20Directory/2.%20Adding%20a%20Domanin%20Controller%20.png)

After the role installation, we promote the server to a **Domain Controller**, creating a new forest and domain (e.g., `corp.local`). This step includes setting a DSRM password and configuring DNS integration.

---

### 3. Domain Configuration Confirmation
![Domain Configuration Confirmation](Deploying%20Active%20Directory/3.%20.png)

This step confirms the successful setup of our new domain. The system restarts as part of the Domain Controller promotion process.

---

### 4. Active Directory Users and Computers
![Active Directory Console](Deploying%20Active%20Directory/4.%20Active%20Directory%20users%20and%20computers.png)

Once the server is promoted, we open the **Active Directory Users and Computers** console. This GUI allows management of users, groups, and organizational units (OUs).

---

### 5. Creating an Admins Folder
![Creating Admins OU](Deploying%20Active%20Directory/5.%20Creating%20Admins%20folder%20.png)

We create a new **Organizational Unit (OU)** named `Admins` to logically separate and manage admin-level users. OUs help organize and apply group policies effectively.

---

### 6. Creating a New User
![Creating a New User](Deploying%20Active%20Directory/6.%20Creating%20a%20new%20user%20.png)

We create a new user account within the `Admins` OU. User accounts in AD represent real individuals and their credentials used to authenticate across the network.

---

### 7. Adding User to Domain Admins
![Adding to Domain Admin Group](Deploying%20Active%20Directory/7.%20Adding%20employee%20to%20Domain%20Admin%20Security%20group%20.png)

The new user is added to the **Domain Admins** security group. This grants them elevated permissions across the domain, including full control over all domain controllers.

---

### 8. Adding a Client to the Domain
![Joining Client to Domain](Deploying%20Active%20Directory/8.%20Adding%20client%20to%20Domain%20.png)

We switch to a Windows client machine and initiate the process to join it to our domain (`corp.local`). This allows centralized authentication and management via AD.

---

### 9. Successfully Joined Client
![Success Join](Deploying%20Active%20Directory/9.%20succsesfully%20added%20client%20to%20domain.png)

The client was successfully joined to the domain. A restart is typically required to complete this process.

---

### 10. Client Now in Domain
![Client in Domain](Deploying%20Active%20Directory/10.%20Client%20is%20now%20in%20our%20Domain%20.png)

We log in with our domain credentials, confirming the client is now part of the AD domain. This means user policies, network drives, and other domain resources can be accessed securely.

---

## 🚀 Skills Demonstrated

- Windows Server 2019/2022
- Active Directory Domain Services
- Organizational Units and Group Policies
- Domain Controller configuration
- User & Group Management
- Client machine domain joining

---

## 💼 Why This Matters

This lab reflects hands-on experience with a foundational infrastructure technology used in nearly every mid-to-large business environment. As a future IT professional, being able to deploy and manage Active Directory proves I’m ready to support real-world enterprise environments.

---
