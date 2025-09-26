# ElevateLabs-Task-4
# 🔥 Windows Firewall Port Blocking Demo

Demonstration of **network security** by blocking insecure ports using **Windows Defender Firewall with Advanced Security**.  
This demo particularly focuses on **blocking Telnet (port 23)** for improved system security.

---

## 🔍 Overview
- **Scenario:** Blocking legacy Telnet service (port 23)  
- **Method:** Inbound rule creation (via GUI & PowerShell)  
- **Result:** Telnet traffic fully blocked  

---

## 🛡️ Why Block Port 23?
- Telnet transmits all data in **plaintext**  
- Legacy protocol with **no encryption**  
- Common target for **brute-force attacks**  
- Secure alternative: **SSH (port 22)**  

---

## 📂 Repository Contents  
- `windows_firewall_before_block.png` → Original config
- `create_new_rule.png` → Custom Telnet block rule
- `windows_firewall_after_blockrule.png` →  Modified config
- `testing_rule.png` → Validation results 

---

## 🎯 Learning Objectives
- Understand **Windows Firewall inbound rules**  
- Learn **port-level access control** for security  
- Apply basic **network hardening practices**  

---

## 📝 Disclaimer
This demo is for **educational purposes only**.  

