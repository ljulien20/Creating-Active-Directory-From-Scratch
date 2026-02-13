# Creating-Active-Directory-From-Scratch

<h2>Description</h2>
Configured and installed Active Directory Domain Services on a Windows Server virtual machine. Promoted the server to a domain controller, created a domain environment, and verified basic domain functionality for user and system management.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Active Directory</b>
- <b>Windows Server</b> 

<h2>Environments Used </h2>

- <b>Virtual Machine</b> 

<h2>Program walk-through:</h2>

<p align="center">
virtual machine was created with Windows Server and server was promoted to a domain controller and Active Directory was installed.: <br/>
<img width="2558" height="1320" alt="Screenshot 2025-12-17 213035" src="https://github.com/user-attachments/assets/091f3d11-029c-4141-9665-f39861636578" />
<br />
<br />
Then, AD created the domain, which was changed to WESTWOOD shortly after: <br/>
<img width="2527" height="1346" alt="Screenshot 2025-12-17 212823" src="https://github.com/user-attachments/assets/c0449dd9-c0d9-4ef1-afd8-c4845a47e4b2" />
<br />
<br />
Once AD domain is created, I created organizational units (OUs) for different departments: <br/>
<img width="1339" height="888" alt="Screenshot 2025-12-24 181520" src="https://github.com/user-attachments/assets/83f997c2-a071-4318-9f20-84c09a465b00" />
<br />
<br />
I created user accounts and groups within these OUs: <br/>
<img width="1094" height="816" alt="Screenshot 2025-12-31 194043" src="https://github.com/user-attachments/assets/ef2ecf94-777f-4925-8fa2-ad76975ea395" />
I configure GPOs to automatically map network drivers for users on the domain. This helps with having to map the drive on each device manually. I will start by making a shared folder. <br/>
<img width="1344" height="948" alt="Screenshot 2026-01-01 133008" src="https://github.com/user-attachments/assets/b54dc047-00ac-4831-b49c-bb66fe991cd1" />
<br />
EVERYONE in the domain has permission to read this file now:
<img width="1372" height="934" alt="Screenshot 2026-01-01 133051" src="https://github.com/user-attachments/assets/0906a860-5e68-48bf-8565-0cf5ae38f438" />
<br />
I configured the SHARED file to the "S" drive on the Drive Maps page after the group policy is made for Mapped Drives. (edited)Thursday, January 1, 2026 5:58 PM

<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
