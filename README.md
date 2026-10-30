# NETWORKWALKSKOKO-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
Week 1 repository for NETWORKWALKS
Cybersecurity Lab Environment Setup - Building an isolated virtual lab for penetration testing and ethical hacking practice

**📌 Project Overview**

This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.
The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.
The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

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

**Problems Encountered**

The manual IP is not working; only DHCP is working, and it is assigning 10.0.0.3 as the Kali IP.

**Solutions**

I will keep working on it

**Security & Ethical Use**

This laboratory is intended strictly for educational purposes only.

**🔗 Tools & Resources**

VirtualBox: https://virtualbox.org/wiki/Downloads
Kali Linux: https://kali.org/get-kali

**👤 Author**

Koko Adeola
LinkedIn: https://www.linkedin.com/in/adeola-koko-cyber/

**📌 Project Information**

Program Name: Cybersecurity at Networkwalks | Week: 01 | Project: Cybersecurity & Pentesting Lab Setup | Repository: GitHub
For NETWORKWALKS Batch B084
