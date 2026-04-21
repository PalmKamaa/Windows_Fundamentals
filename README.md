# 🖥️ Windows Fundamentals – Hack The Box

🔗 Module Link: https://academy.hackthebox.com/achievement/2272384/49  

---

##  Overview

This repository contains my notes and hands-on work from completing the **Windows Fundamentals** module on Hack The Box Academy.

The goal of this module was to understand how Windows works both from a normal user perspective and from a security/penetration testing point of view. I got to interact with a real Windows environment and practice different commands and configurations.

---

##  Tools Used

During this module, I worked with a mix of Windows and Linux tools:

- **Kali Linux** – Main attacking machine  
- **xfreerdp3** – Used for RDP connection  
- **OpenVPN** – To connect to the HTB lab network  
- **PowerShell** – For system interaction and enumeration  
- **Command Prompt (cmd)** – Basic Windows commands  
- **WMI (Windows Management Instrumentation)** – System information gathering  
- **MMC (Microsoft Management Console)** – System management  
- **Windows Defender** – Basic security monitoring  

---

##  What I Learned

- How Windows is structured internally  
- How to connect to a Windows machine remotely using RDP  
- Basic system enumeration using PowerShell and WMI  
- File systems (NTFS, FAT32, exFAT)  
- Managing permissions (NTFS vs Share permissions)  
- Working with services and processes  
- Using tools like PowerShell, WMI, and MMC  
- Windows security concepts like SIDs, ACLs, UAC  

---

##  Remote Connection (RDP)

I connected to the target machine using Kali Linux.

At first, this command didn’t work:

```bash
xfreerdp /v:<targetIP> /u:htb-student /p:Password
```
---
## Screenshots


<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/27c4da85-1b6e-4e46-8f86-a939709cd4e5" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/c5f894ed-053d-4406-b02f-13729d7a89ea" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/dd0f830d-4749-4229-9695-f746143c32d2" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/008833ba-dd3d-462d-840e-cd2ae656993a" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/00c745fd-6c60-4ba4-9377-5b5fa6a07bb5" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/c5b515ad-6099-4b76-b6aa-7132d4e531eb" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/cbaa38bc-6c7c-4cde-be3f-32f2b29326d0" />

<img width="701" height="394" alt="image" src="https://github.com/user-attachments/assets/d011a1c5-97b1-4dfa-a1b0-056e438a8f5c" />



