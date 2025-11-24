# Born2beroot

Born2beroot is a system administration project from the 42 curriculum.
The goal is to create and configure a secure Linux virtual machine from scratch, following strict technical and security requirements.

## 🎯 Project Objectives

* Install and configure a **Debian-based virtual machine** without a graphical interface.
* Understand the fundamentals of system administration, users, permissions, networking, and services.
* Apply security best practices through firewall configuration, password policies, and service hardening.
* Learn to manage and monitor a Linux environment using system tools.

## 🛠️ What I Implemented

This project was fully configured inside a **VirtualBox VM** (not inside the GitHub repo).
Main components:

### **System Setup**

* Fresh installation of **Debian (no GUI)**
* Partitioning using **LVM**
* Creation of users and groups, including a restricted user

### **Security**

* Enforced **strong password policies**
* Configured **sudo** with strict access rules and logging
* Enabled and configured **UFW firewall**
* SSH server installed and restricted (no root login, custom settings)

### **Services & Automation**

* **SSH** access for remote connections
* Scheduled automated tasks using **cron**
* System monitoring script** (checks CPU, RAM, disk usage, network, etc.), executed via `cron`

## 📚 What I Learned

Through Born2beroot, I gained hands-on experience with:

* Linux system installation and administration
* User management, permission models, and privilege separation
* Service configuration (SSH), firewalling, and secure defaults
* Process monitoring and automation
* Working in a controlled, reproducible environment using virtual machines

