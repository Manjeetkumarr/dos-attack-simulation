# 🛡 DoS Attack Simulation (Cybersecurity Project)

## 📌 Overview
This project demonstrates a Denial of Service (DoS) attack in a controlled virtual lab environment using Kali Linux and Metasploitable2.

## 🎯 Objectives
- Understand DoS attack concept
- Simulate ICMP flooding attack
- Analyze traffic using Wireshark

## 🛠 Tools Used
- Kali Linux
- Metasploitable2
- Wireshark
- VMware Workstation
- hping3

## ⚙ Setup
- Two virtual machines connected in same network
- Kali Linux (Attacker)
- Metasploitable2 (Target)

## 🚀 Execution
- Identified target IP using `ifconfig`
- Captured traffic using Wireshark
- Performed ICMP flood attack using hping3

## 📊 Results
- High ICMP traffic observed
- Packet loss reached ~100%
- Target system slowed down

## 📷 Screenshots
<img width="770" height="512" alt="hping3 Attack Execution" src="https://github.com/user-attachments/assets/bd04d7bb-010b-4c52-bb57-4a086885a95b" />
.
<img width="965" height="714" alt="Wireshark ICMP Traffic" src="https://github.com/user-attachments/assets/ddbf2d5f-dba3-41ba-b6d7-b12702f4047b" />
.
<img width="820" height="351" alt="Packet Details1" src="https://github.com/user-attachments/assets/341dfe8b-d00f-443c-a9cc-0d7e3d756c68" />
.
<img width="1095" height="522" alt="Packet Details2" src="https://github.com/user-attachments/assets/fbcd3b63-8621-484a-a85d-7168e2fff765" />


## 📄 Report
[Download Report](./DoS_Project_Report_CyberSecurity.pdf)

## ⚠ Ethical Note
This project is for educational purposes only. Do not misuse.
