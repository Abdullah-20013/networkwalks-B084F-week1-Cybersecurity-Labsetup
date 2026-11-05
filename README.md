# 🔐 Cybersecurity Virtual Lab

<h3 align="center">Kali Linux | VirtualBox | Windows 11</h3>

<p align="center">
  <strong>Building a Hands-on Cybersecurity Learning Environment</strong>
  <br>
  Virtualization • Linux • Networking • Ethical Hacking
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Host-Windows%2011-blue?logo=windows11" alt="Windows 11">
  <img src="https://img.shields.io/badge/VirtualBox-Virtualization-183A61?logo=virtualbox" alt="VirtualBox">
  <img src="https://img.shields.io/badge/OS-Kali%20Linux-557C94?logo=kalilinux" alt="Kali Linux">
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-red" alt="Cybersecurity">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RAM-2GB-orange">
  <img src="https://img.shields.io/badge/CPU-2%20Cores-blue">
  <img src="https://img.shields.io/badge/Network-NAT%20Network-green">
  <img src="https://img.shields.io/badge/Storage-20GB-lightgrey">
</p>

---

---

## 📌 Project Overview

This project demonstrates the creation and configuration of a personal Cybersecurity Virtual Lab using **Oracle VirtualBox and Kali Linux**, running on a Windows 11 host machine.

The purpose of this lab is to establish a controlled virtual environment for learning Linux administration, networking fundamentals, and practical cybersecurity concepts.

This environment serves as a foundation for future ethical hacking exercises, network security analysis, and penetration testing practice.

## 🎯 Project Objectives

- Install and configure Oracle VirtualBox.
- Deploy Kali Linux as a virtual machine.
- Configure virtual machine hardware resources.
- Set up a NAT Network for virtual networking.
- Understand IP addressing and network connectivity.
- Practice Linux terminal commands.
- Establish a foundation for ethical hacking and security testing.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Windows 11 | Host Operating System |
| Oracle VirtualBox | Virtualization Platform |
| Kali Linux | Security Testing Operating System |
| NAT Network | Virtual Network Configuration |
| Linux Terminal | Command-Line Operations |
| GitHub | Project Documentation |

## 🏗️ Lab Architecture

The lab uses Windows 11 as the host operating system, Oracle VirtualBox as the virtualization platform, and Kali Linux as the guest operating system.

### Architecture Diagram

```text
       HOST MACHINE
         Windows 11
              |
              |
       Oracle VirtualBox
              |
              |
        NAT Network
              |
              |
        Kali Linux VM
              |
              |
     Cybersecurity Tools
```

## ⚙️ Virtual Machine Configuration

The following hardware resources were allocated to the Kali Linux virtual machine:

| Component | Configuration |
|---|---|
| Host OS | Windows 11 |
| Virtualization | Oracle VirtualBox |
| Guest OS | Kali Linux |
| Allocated RAM | 2 GB |
| CPU Cores | 2 |
| Virtual Disk | 20 GB |
| Network Adapter | NAT Network |

## 🚀 Lab Setup Procedure

### Step 1: Install Oracle VirtualBox

Downloaded and installed Oracle VirtualBox on the Windows 11 host machine.

Official website: https://www.virtualbox.org/

### Step 2: Download Kali Linux

Downloaded the Kali Linux distribution from its official website.

Official website: https://www.kali.org/

### Step 3: Create the Kali Linux Virtual Machine

Created a virtual machine in Oracle VirtualBox and configured the following resources:

- RAM: 2 GB
- CPU: 2 cores
- Virtual Disk: 20 GB
- Operating System: Kali Linux

### Step 4: Configure NAT Network

Configured the virtual machine network adapter to use NAT Network mode.

NAT Network allows virtual machines connected to the same configured virtual network to communicate with one another while using network address translation for external connectivity.

### Step 5: Boot Kali Linux

Started the Kali Linux virtual machine and completed the initial operating system setup.

Verified that the Kali Linux desktop environment loaded successfully.

### Step 6: Verify Network Configuration

Used Linux terminal commands to inspect the network configuration.

**Check IP address:**

```bash
ip addr
```

**Check network interfaces:**

```bash
ip link
```

**Check routing table:**

```bash
ip route
```

**Test external connectivity:**

```bash
ping -c 4 8.8.8.8
```

**Test DNS resolution:**

```bash
nslookup google.com
```

## 📸 Screenshots & Evidence

Screenshots documenting the lab setup are organized in the `screenshots/` directory.

| Screenshot | Description |
|---|---|
| 01 | VirtualBox main dashboard |
| 02 | Kali Linux VM configuration |
| 03 | Kali Linux desktop environment |
| 04 | NAT Network configuration |
| 05 | IP address verification |
| 06 | Network connectivity test |

*Add your actual screenshots here as the project progresses.*

## 🧪 Lab Verification Checklist

- [ ] Oracle VirtualBox installed successfully.
- [ ] Kali Linux virtual machine created.
- [ ] RAM and CPU resources configured.
- [ ] Virtual disk configured.
- [ ] NAT Network configured.
- [ ] Kali Linux boots successfully.
- [ ] Network interface detected.
- [ ] IP address verified.
- [ ] Internet connectivity tested.
- [ ] DNS resolution tested.

## 🧠 Skills & Knowledge Gained

This project helped me develop practical knowledge of:

- Virtualization using Oracle VirtualBox.
- Kali Linux installation and configuration.
- Linux command-line fundamentals.
- Virtual networking concepts.
- IP addressing and network interfaces.
- Network connectivity troubleshooting.
- Cybersecurity lab preparation.
- Technical documentation using GitHub.

## 🔮 Future Improvements

I plan to expand this cybersecurity lab with additional virtual machines and practical security exercises.

Planned activities include:

- Adding a Windows virtual machine.
- Creating an isolated attacker-and-target environment.
- Practicing network scanning using Nmap.
- Analyzing network traffic using Wireshark.
- Exploring vulnerability assessment tools.
- Practicing ethical hacking on intentionally vulnerable machines.
- Documenting additional cybersecurity projects.

## ⚠️ Disclaimer

This lab is designed exclusively for educational purposes and authorized cybersecurity testing.

All security testing activities will be conducted only on systems that I own or have explicit permission to test.

## 👨‍💻 Author

**[Your Name]**

Cybersecurity Enthusiast | Linux Learner | Aspiring Security Professional

GitHub: [Your GitHub Profile](https://github.com/)

---

⭐ If you find this project useful, consider giving this repository a star!
