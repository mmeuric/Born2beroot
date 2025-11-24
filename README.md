# Born2beroot

Born2beroot is a system administration project from the 42 curriculum.
The goal is to create and configure a secure Linux server inside a virtual machine, following strict guidelines related to users, permissions, security policies, and service configuration.

## 🎯 Project Objectives

* Install and configure a **Debian virtual machine** without any graphical interface.
* Learn the basics of system administration and hardening.
* Apply strict security rules and enforce strong password policies.
* Set up essential services while keeping the system minimalistic and secure.
* Understand and manage virtualization using **VirtualBox**.

## 🛠️ What I Implemented

All work for this project was done directly inside a VirtualBox VM (not stored in the repository).

### **System Setup**

* Installed **Debian (no GUI)**
* Configured **LVM** with encrypted partitions
* Customized hostname and system settings

### **Security & Access**

* Configured **SSH** (port 4242, no root login)
* Enabled and configured **UFW** firewall (only port 4242 allowed)
* Set up **sudo** with strict rules, logging, limited paths, and authentication attempts
* Applied a **strong password policy** (complexity, expiration, warnings)

### **Users & Permissions**

* Created and configured a non-root user
* Assigned proper groups (`sudo`, `user42`)
* Managed privileges using sudoers rules

### **Automation & Monitoring**

* Implemented a **monitoring script** (`monitoring.sh`) triggered by **cron**
* Displays system metrics every 10 minutes (CPU, RAM, disk, network, sudo stats…)

## 📚 What I Learned

This project allowed me to build practical skills in:

* Linux installation & server administration
* Firewalling, SSH hardening, and privilege management
* Secure system configuration and auditing
* Shell scripting and automated monitoring
* Virtualization concepts with VirtualBox

The repository contains only documentation, as the configuration work exists entirely inside the VM.


