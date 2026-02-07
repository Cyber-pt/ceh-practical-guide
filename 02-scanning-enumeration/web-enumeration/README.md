## 🎯 Objective
To enumerate web server directories and hidden resources to identify exposed attack surfaces.

## 🛠 Tools Used
- dirb
- gobuster
- nmap

## 📌 Steps Performed
1. Verified web server availability  
2. Performed directory brute forcing using Dirb  
3. Enumerated hidden paths using Gobuster  

## ✅ Result
Discovered hidden directories and web resources that were not directly visible from the main website.

## ⚠️ Security Impact
Exposed directories and admin panels can be exploited to gain unauthorized access or sensitive information.

## 🛡 Prevention & Mitigation
- Disable directory listing  
- Restrict access to admin pages  
- Remove unused files and directories  
- Use web application firewalls  

### 📸 Evidence

![Web Port Check](web1.png)  
![Dirb Results](web2.png) 
![Dirb Results](web3.png) 
![Dirb Results](web4.png) 
![Gobuster Results](web5.png)
![Gobuster Results](web6.png)
![Gobuster Results](web7.png)
