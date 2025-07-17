# 🧰 My SysAdmin Homelab

A personal homelab project built for hands-on experience with system administration, networking, and automation.

---

## 🏠 Lab Overview

- **Purpose**: Practice Windows/Linux administration, Active Directory, scripting, networking, and automation.
- **Platform**: VirtualBox / VMware / Proxmox / Cloud
- **OS Used**:
  - Windows Server 2022 (Domain Controller, DNS, DHCP)
  - Ubuntu Server 22.04 (Web, SSH, File Share)
  - Windows 10 Client

---

## 🛠️ Services Setup

| Hostname | OS | Role | IP Address | Key Features |
|----------|----|------|------------|--------------|
| DC01     | Windows Server | Domain Controller | 192.168.1.10 | AD, DNS, DHCP |
| UB01     | Ubuntu Server | Web/File Server | 192.168.1.20 | Apache, Samba |
| CL01     | Windows 10 | Client PC | 192.168.1.30 | Joined to domain |

---

## ⚙️ Key Tasks Completed

- [x] Setup Active Directory and Group Policies
- [x] Configured internal DNS/DHCP
- [x] Installed and secured Apache/Nginx
- [x] Built PowerShell and Bash scripts
- [x] Created scheduled backups (rsync, Task Scheduler)
- [ ] Set up monitoring with Zabbix/Nagios
- [ ] Added pfSense firewall

---

## 📜 Scripts & Configs

This repo includes:
- `powershell/` - AD automation scripts
- `bash/` - Backup and maintenance scripts
- `configs/` - Config files (Samba, Apache, DNS)

---

## 🗺️ Network Diagram

> Insert your network diagram image or link here.

---

## 📖 Documentation

All setup steps, configs, and notes are documented in `/docs` folder.

---

## 📌 Next Goals

- Add cloud integration (Azure AD or AWS CLI)
- Deploy Docker containers for services
- Document security hardening steps

---

## 📬 Contact

Have suggestions or want to collaborate? Feel free to connect on [LinkedIn](https://www.linkedin.com).

