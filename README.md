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
