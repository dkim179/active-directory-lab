# 🖥️ Active Directory Home Lab

This project is a simulation of a small enterprise network environment built using VMware Workstation 17.  
The lab includes Windows Server as a Domain Controller, pfSense firewall, multiple VLANs, DHCP, and Group Policy configurations.

---

## 🛠️ Lab Environment

| Component | Details |
|----------|---------|
| Hypervisor | VMware Workstation 17 |
| OS | Windows Server 2019, Ubuntu 20.04 |
| Firewall |
| Tools | PowerShell, Bash, Group Policy, AD DS |

---

## ⚙️ What I Configured

- [x] Installed and promoted **Active Directory Domain Services (AD DS)**
- [x] Created **Organizational Units (OUs)** and users/groups
- [x] Applied **Group Policies (GPOs)** (e.g., password policies, desktop backgrounds)
- [x] Set up **NTFS and Share permissions** on file servers
- [x] Wrote PowerShell scripts for:
  - User creation automation
  - Scheduled backups
  - System monitoring and logging

---

## 🔐 Security Best Practices Demonstrated

- Role-based access control
- Principle of least privilege (GPO + NTFS)
- VLAN segmentation
- Local vs Domain firewall rules

---

## 📸 Screenshots

| Feature | Screenshot |
|--------|-------------|
| AD DS Installation | ![](./screenshots/ad_installation.png) |
| Group Policy Example | ![](./screenshots/group_policy.png) |
| pfSense VLAN Setup | ![](./screenshots/pfsense_vlan.png) |

---
