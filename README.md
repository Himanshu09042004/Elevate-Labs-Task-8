# Elevate-Labs-Task-8
A VPN encrypts your internet traffic and hides your IP, boosting privacy and security. It's useful for public Wi-Fi, bypassing geo-blocks, and avoiding tracking. However, it may slow speed and doesn't ensure full anonymity. Free VPNs often have limits.

# 🛡️ Task 8 – Working and Understanding VPN

## 🎯 Objective

To understand the concept, working, and practical usage of a Virtual Private Network (VPN) by setting up and configuring a free VPN on Kali Linux. The task includes verifying IP changes, ensuring encrypted communication, and documenting benefits and limitations of VPNs.

---

## 🧰 Tools & Environment

- **Operating System:** Kali Linux
- **VPN Client:** ProtonVPN CLI (Free Tier)
- **Browser:** Mozilla Firefox
- **Verification Site:** [whatismyipaddress.com](https://whatismyipaddress.com)
- **Terminal Tools:** `curl`, `ip`, `ping`

---

## 🔧 Setup and Execution Steps

### ✅ Step 1: ProtonVPN Registration

- Created a free account at: [https://protonvpn.com](https://protonvpn.com)

### ✅ Step 2: Install ProtonVPN CLI

```bash
sudo apt update
sudo apt install protonvpn-cli
