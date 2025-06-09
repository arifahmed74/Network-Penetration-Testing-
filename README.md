# 🔓 Wireless Penetration Testing Project

**Course:** CSCI 400-1  
**Presented by Group 8:**  
- Folusho Adeoti  
- Arif Ahmed  
- Josue Nunez  

---

## 🧠 Project Overview

This project explores wireless penetration testing techniques used to identify and exploit vulnerabilities in wireless networks. Our objectives included:

- Performing **packet sniffing** to capture sensitive network data  
- Conducting **packet analysis** to identify key information like IP/MAC addresses  
- Executing **Deauthentication attacks** to disrupt connectivity  
- Proposing **mitigation strategies** to improve wireless security  

---

## 🎯 Goals

- Understand and simulate common wireless network attacks  
- Identify vulnerabilities in typical wireless setups  
- Learn how to use industry-standard tools in a controlled testing environment  
- Propose real-world solutions to defend against these attack types  

---

## 🔄 Penetration Testing Phases

1. **Reconnaissance** – Gather preliminary information  
2. **Scanning** – Identify vulnerabilities using automated tools  
3. **Gaining Access** – Exploit vulnerabilities to gain control  
4. **Analysis & Reporting** – Document findings and evaluate risks  

---

## ⚙️ Tools & Hardware Used

- **Kali Linux (VM)**  
- **Wireless USB WiFi Adapter**  
- **Aircrack-ng Suite**  
- **Wireshark**  
- **Bluetooth Utilities (hcitool, hciconfig)**

---

## 🧪 Attacks Performed

- **Deauthentication Attack:**  
  Used to forcibly disconnect devices by sending fake deauth frames

- **Packet Sniffing:**  
  Captured network packets to observe sensitive data transfers

- **Packet Analysis:**  
  Analyzed packet content to extract IP addresses, MACs, and protocols used

---

## 🛡️ Proposed Security Solutions

### For Deauthentication Attacks
- Deploy **Wireless Intrusion Detection/Prevention Systems (WIDS/WIPS)**  
- Configure APs to block excessive deauth frames or apply rate limiting  
- Monitor logs for suspicious deauthentication behavior  

### For Packet Sniffing
- Enforce **WPA2/AES encryption** for WiFi networks  
- Use **HTTPS/SSH** for all sensitive web and remote access  

### For Packet Analysis
- Deploy **IDS/IPS** systems for anomaly detection  
- Apply **network segmentation** and strong **access controls**  
- Encrypt sensitive data in transit  

---

## 🌍 Real-World Examples

- **Equifax Data Breach (2017):**  
  Missed vulnerability during pen testing led to exposure of 143M records.

- **Canadian Government Breach (2019):**  
  Successful penetration testing helped uncover and patch multiple critical flaws.

---

## ⚠️ Challenges Faced

- Bluetooth tools like `hcitool` and `hciconfig` failed in some VMs; resolved by switching to older Kali version  
- Initial WiFi adapter was incompatible with Kali; had to be replaced  

---

## ✅ Conclusion

This project demonstrated the risks present in wireless networks and the importance of proactive testing and mitigation. With the right tools, knowledge, and planning, organizations can greatly enhance their wireless security posture.

---

## 📎 Additional Resources

- [Aircrack-ng Documentation](https://www.aircrack-ng.org/doku.php)  
- [Wireshark User Guide](https://www.wireshark.org/docs/wsug_html_chunked/)  
- [Kali Linux Tools](https://tools.kali.org/)

---

## 📂 How to View the Presentation

[📑 Download PowerPoint Presentation](./docs/Wireless_Penetration_Testing_Group8.pptx)  


