# 🧩 Find Your IP Address
<p align="center">
<img src="https://i.imgur.com/BzeSfFp.png" height="80%" width="80%" alt="Find Your IP Address Project Banner"/>
</p>

<h1>🔍 Introduction</h1>
Every device connected to a network has two types of IP addresses:  

  -   🌐 **Public IP Address:** Assigned by your Internet Service Provider (ISP) and used for communicating with websites and online services.  
  -   🏠 **Private IP Address:** Used within your local network to identify your device.

This tutorial walks through how to locate both **public** and **private** IP addresses on **Windows**, **Linux**, and **macOS**.  
It also reinforces key networking fundamentals for IT Support and Cloud learners.

---

<h2>🌐 Environments and Technologies Used</h2>

- Windows 10 / 11  
- Command Prompt & PowerShell  
- Linux Terminal (Optional WSL2 Extension)  
- Internet Connection  
- Basic Networking Tools (`ipconfig`, `ip addr`, `curl`)

---

<h2>💻 Operating Systems Tested</h2>

- 🪟 Windows 10  
- 🐧 Linux (WSL2 - Ubuntu 22.04)  
- 🍎 macOS Ventura  

---

<h2>🧠 Understanding IP Addresses</h2>

| Type | Visibility | Description | Example |
|------|-------------|--------------|----------|
| 🏠 **Private IP** | Local Network Only | Identifies your device inside your router’s LAN | 192.168.1.10 |
| 🌐 **Public IP** | Internet Visible | Identifies your network on the internet (assigned by ISP) | 71.188.48.38 |

---

<h2>🪟 Windows Instructions</h2>

## 🎯 Step 1 — Understand the Goal

You’re going to find:

- 🏠 **Private IP address** → the one your **router** assigns to your computer  
- 🌐 **Public IP address** → the one your **Internet Service Provider (ISP)** assigns to your entire home network  

These are **network fundamentals** — every IT professional needs to know how to find and understand them.

---

## 🧠 Step 2 — Difference Between Public and Private IP

| Type | Description | Example |
|------|--------------|----------|
| 🏠 **Private IP** | Identifies your device inside your local network (used by your router) | `192.168.1.10`, `10.0.0.5` |
| 🌐 **Public IP** | Identifies your entire network on the internet | `73.124.99.21` |

💡 **Note:**  
Your home might have multiple devices, each with their own **private IP**, but they all share **one public IP** when accessing the internet.

## 💻 Step 3 — Finding Your Private IP Address (Windows)

We’ll use **Command Prompt (cmd)** for this section.

---

### 🪟 Step 3.1 — Open Command Prompt

1. Press **Windows Key + R**  
2. Type:
   ```bash
   cmd

   ---

### 🔍 Step 3.2 — Run the Command

1. In the Command Prompt window, type:ipconfig
2. Then press Enter to execute the command.
You’ll see a list of network adapters and their IP configuration details.

<img width="1536" height="1024" alt="step 3 B - run the command" src="https://github.com/user-attachments/assets/c47e50d3-b711-4c05-99e0-e31758956d09" />

   ---

### 🔍 📡 Step 3.3 — Identify Your Private IP Address

1. Look for your active network adapter, usually named:
2. Wireless LAN adapter Wi-Fi:
   IPv4 Address. . . . . . . . . . . : 192.168.1.12

3. The number next to IPv4 Address (e.g., 192.168.x.x or 10.x.x.x) is your Private IP Address.

<p align="center"> <img width="1536" height="1024" alt="step 3 C - IP address found" src="https://github.com/user-attachments/assets/5fa2e4f3-7eca-4426-afb8-c9b7889ede0b" />

### 🌐 Step 4 — Finding Your Public IP Address (Windows)

1. Using Command Line:

Still in Command Prompt, type: curl ifconfig.me

2. That’s your Public IP address.

<p align="center"><img width="1024" height="1024" alt="step 4" src="https://github.com/user-attachments/assets/dc164b5e-dfea-4597-ae8d-9762e7a3a3e4" />

## ✅ Conclusion

In this project, we successfully demonstrated how to:

- Identify your **Private IP Address** using `ipconfig` in Windows Command Prompt  
- Retrieve your **Public IP Address** using `curl ifconfig.me` or PowerShell  
- Understand the difference between **local (private)** and **external (public)** network addresses  
- Apply foundational **networking concepts** that are essential for Cloud and IT Support environments  

This exercise reinforces the importance of understanding IP addressing — a skill used daily in troubleshooting, networking, and cloud infrastructure management.

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience with:

- 🧠 Understanding **Private vs Public IP Addressing**  
- 💻 Using **Command Prompt** and **PowerShell** for network diagnostics  
- 🧩 Identifying and interpreting **IPv4 configurations**  
- ☁️ Strengthening core **network troubleshooting skills**  
- 🔐 Applying networking fundamentals relevant to **Cloud Engineering** and **DevOps**  
- 📸 Practicing proper **documentation and screenshot redaction** for professional portfolios






