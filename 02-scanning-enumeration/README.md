# 🔍 Scanning & Enumeration Phase

This phase focuses on actively discovering live systems, open ports, running services, and exposed resources within a target environment.


## 🎯 Objective

To identify reachable hosts, open ports, service versions, vulnerabilities, and misconfigurations that can be leveraged for exploitation.


## 🛠 Tools Used

- Nmap  
- enum4linux  
- smbclient  
- dirb  
- gobuster  
- OpenVAS (optional)  


## 📌 Steps Performed

1. Discovered live hosts within the network  
2. Scanned open TCP and UDP ports  
3. Identified running services and versions  
4. Detected vulnerabilities and misconfigurations  
5. Enumerated SMB shares and users  
6. Tested FTP access and permissions  
7. Discovered hidden web directories and resources  


## ✅ Result

Successfully mapped network services, identified exposed entry points, and discovered vulnerable services across target systems.


## ⚠️ Security Impact

Scanning reveals weak points that attackers can exploit to gain unauthorized access and escalate privileges.


## 🛡 Prevention & Mitigation

- Close unused ports  
- Patch vulnerable services  
- Use firewalls and monitoring  
- Restrict service access  
- Regular vulnerability assessments  


📂 Each subfolder contains detailed scanning labs with evidence and step-by-step execution.
