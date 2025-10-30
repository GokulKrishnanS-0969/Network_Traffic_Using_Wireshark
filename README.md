# Network_Traffic_Using_Wireshark
Capture live network packets and identify basic protocols and traffic types.
# 🛡️ Network Traffic Capture — Wireshark (Kali)

**Task:** Packet Capture & Protocol Analysis (HTTP, TCP, DNS)  
**Date:** 2025-10-27  
**Author:** Gokul Krishnan S  

---

## 🎯 Objective
Capture and analyze live network traffic on **Kali Linux** using the **Wireshark GUI** to understand how different network protocols like **HTTP**, **TCP**, and **DNS** operate in real time.

---

## 🧰 Tools Used
- 🐧 **Operating System:** Kali Linux  
- 🧠 **Tool:** Wireshark (Graphical Interface, pre-installed on Kali)

---

## ⚙️ Method

### 🟢 Step 1 — Launch Wireshark
Open Wireshark from the Kali Applications menu:  
```bash
Applications → Sniffing & Spoofing → Wireshark

🟡 Step 2 — Start Capture

Select the active network interface showing live packets.

Click Start Capturing Packets ▶️.

Perform normal network activity (e.g., browse websites).

Click Stop ⏹ once you have enough data.

File → Save As → capture_result.pcap

# DNS packets
dns

# TCP packets
tcp

# HTTP packets
http

Right-click packet → Export Packet Dissections → As Plain Text

✅ *This documentation demonstrates awareness of browser-based security threats and good cybersecurity practices.*
