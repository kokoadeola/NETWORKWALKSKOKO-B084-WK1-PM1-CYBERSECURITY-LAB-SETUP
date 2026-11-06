<div align="center">

  # NETWORKWALKSKOKO-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
Week 1 repository for NETWORKWALKS


🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>

This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux, Android 9, and Windows 10
The lab creates a controlled environment where you can safely and repeatedly perform cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities.
The lab is configured on a private virtual network so you can add additional machines later and use them as targets for authorized security testing.

**Step 1. Install VirtualBox**

VirtualBox was installed as the hypervisor.

**Step 2. Create the NAT Network**

A dedicated NAT Network was created in VirtualBox.

Configuration: Network Name: NatNetwork IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabled
<img width="1169" height="691" alt="NAT IP" src="https://github.com/user-attachments/assets/aa961458-fe31-4911-8832-ed7375677d66" />

**Step 3. Import Kali Linux**

The Kali Linux virtual machine was downloaded from the official Kali Linux website and imported into VirtualBox.

The VM network adapter was configured as follows:

Adapter 1
Attached to: NAT Network
Network:     NatNetwork
Adapter Type: Intel PRO/1000 MT Desktop
The VM was allocated: RAM: 2048 MB
<img width="1283" height="902" alt="kali" src="https://github.com/user-attachments/assets/a5f7740f-793d-4bde-9900-e7b5937eea48" />
A shared folder was also configured for transferring required files between the host operating system and the Kali VM. The folder name is Downloads, and it is on the host machine.

**Step 4. Snapshot of Kali Linux**

<img width="1172" height="701" alt="snapshot" src="https://github.com/user-attachments/assets/91b91354-699c-4936-8af1-144c7be76c66" />

**Step 5. Configure the Kali Linux Network**

<img width="1278" height="873" alt="manual ip" src="https://github.com/user-attachments/assets/bcbd3fb0-e55e-4cd3-8f2f-e76011ff46d7" />
<img width="1270" height="786" alt="ip a" src="https://github.com/user-attachments/assets/8ed1ff47-0377-412b-8ec8-90ff6bbe80ad" />

**Extra Tasks Performed**
**Android 9 installed and used to Ping Kali Linux and Vice Versa**
<img width="916" height="619" alt="kali - and" src="https://github.com/user-attachments/assets/44cba6dc-5e79-4bb9-b7ac-8d0bb4aebe3f" />
<img width="1127" height="792" alt="and - kali" src="https://github.com/user-attachments/assets/84b7ad1d-2dc6-485e-b4b6-c316b346dff8" />

**Windows 10 installed and used to Ping Kali Linux and Vice Versa**
<img width="910" height="558" alt="10 - kali" src="https://github.com/user-attachments/assets/58b65a21-5083-4eb0-a3e2-2709ac22cbca" />
<img width="842" height="642" alt="kali - 10" src="https://github.com/user-attachments/assets/953359b9-4970-446b-82e2-67752e106b06" />


# 🐞 Problems Encountered

The manual IP is not working; only DHCP is working, and it is assigning 10.0.0.3 as the Kali IP.

**Solutions**

I will keep working on it

**Solutions Update**
For this lab, my Kali Linux IP will be 10.0.0.20 

**Security & Ethical Use**

This laboratory is intended strictly for educational purposes only.

**🔗 Tools & Resources**

VirtualBox: https://virtualbox.org/wiki/Downloads
Kali Linux: https://kali.org/get-kali
Windows 10: https://www.microsoft.com/software-download/windows10
Android: https://sourceforge.net/projects/android-x86/files/Release%209.0/

**👤 Author**

Koko Adeola
LinkedIn: https://www.linkedin.com/in/adeola-koko-cyber/

**📌 Project Information**

Program Name: Cybersecurity at Networkwalks | Week: 01 & Extra Tasks | Project: Cybersecurity & Pentesting Lab Setup | Repository: GitHub
For NETWORKWALKS Batch B084
