# Windows Server & Active Directory Lab
<img width="707" height="373" alt="Image" src="https://github.com/user-attachments/assets/ade53755-75e5-4e95-aff7-5c8caf2d6eb3" />

## 📖 Overview
This project documents the creation of an IT support home lab designed to simulate a real-world corporate environment. The lab is configured to perform standard corporate IT support tasks commonly handled in helpdesk and junior IT roles, including user administration, access control, troubleshooting, and system maintenance.

---

## 🔑 Key Skills Covered
- Windows Server installation, configuration, and administration  
- Active Directory user, group, and domain management  
- Domain-joined client support and authentication  
- Patch management and update deployment using Action1  
- Monitoring update execution and endpoint compliance  
- Basic IT security and system maintenance practices  
- Troubleshooting common Active Directory issues  
- Working with virtual machines in a lab environment  

---

## 🧩 Project Breakdown

### Active Directory Setup

<img width="602" height="431" alt="Image" src="https://github.com/user-attachments/assets/966b16dc-ddbb-4ca1-9f35-09e1da36a0f4" />

- Installed Active Directory Domain Services (AD DS) on Windows Server  
- Promoted the server to a Domain Controller  
- Created a new domain for the lab environment  

Active Directory forms the foundation of the lab and enables centralised user management, authentication, and access control, which are core components of day-to-day IT support work.

---

### Account Creation

<img width="602" height="426" alt="Image" src="https://github.com/user-attachments/assets/0d4a46cb-d50d-4f77-b2ef-7e002c35bb7a" />

- Created domain user accounts using Active Directory Users and Computers  
- Organised users into appropriate structures for easier management  

This simulates common helpdesk tasks such as onboarding new users and managing account access.

---

### Patch Management 

<img width="698" height="275" alt="Image" src="https://github.com/user-attachments/assets/87551978-1040-4ddf-9fcd-00164e7ceafd" />

- Implemented patch management using Action1  
- Enrolled the domain controller as a managed endpoint  
- Deployed Microsoft cumulative and .NET Framework updates  
- Monitored update execution and status through the Action1 console  

This demonstrates an understanding of ongoing system maintenance, endpoint management, and the importance of keeping systems secure and up to date in a corporate IT environment.

---

## 🚀 Next Steps
- Configure Group Policy Objects (GPOs)  
- Implement file shares with NTFS permissions  
- Document common troubleshooting scenarios (account lockout, access denied, GPO not applying)
