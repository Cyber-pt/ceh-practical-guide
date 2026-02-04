# 🔍 Reconnaissance & Footprinting Phase

This phase focuses on gathering publicly available information about a target before launching any active attacks.  
Reconnaissance helps attackers understand the target’s digital footprint, infrastructure, and exposed data.

## 🎯 Objective
To collect maximum information about a target domain including ownership details, DNS records, technologies used, subdomains, exposed metadata, and public data using passive and active footprinting techniques.

## 🛠 Tools Used
- whois  
- nslookup  
- dig  
- dnsrecon  
- Google Dorking  
- theHarvester  
- exiftool  
- Web browser analysis 

## 📌 Steps Performed
1. Defined target scope and selected domains for footprinting  
2. Performed WHOIS queries to gather domain registration and ownership information  
3. Collected registrar, name server, and IP allocation details  
4. Enumerated DNS records including A, MX, NS, and TXT records  
5. Attempted DNS zone transfers to check for misconfigurations  
6. Analyzed website technologies to identify CMS, server type, frameworks, and programming languages  
7. Gathered IP and network information including ISP details and geolocation  
8. Conducted OSINT using search engine footprinting techniques and Google dorks  
9. Discovered exposed public endpoints and infrastructure data  
10. Extracted metadata from publicly available documents and files  
11. Enumerated subdomains to expand the attack surface  
12. Attempted email harvesting using automated tools and manual methods 

## ✅ Result
Successfully identified:

- Domain ownership and registrar data  
- DNS infrastructure and name servers  
- Website technologies and exposed endpoints  
- Network and ISP information  
- Publicly accessible metadata  
- Multiple subdomains expanding attack surface 

## ⚠️ Security Impact
Reconnaissance exposes critical infrastructure details that attackers can use to:

- Map networks  
- Discover hidden services  
- Identify weak points  
- Perform targeted attacks  
- Prepare exploitation strategies  

Even public information can significantly reduce attack complexity.

## 🛡 Prevention & Mitigation
- Enable domain privacy protection  
- Restrict DNS zone transfers  
- Remove metadata from public files  
- Hide diagnostic endpoints  
- Monitor exposed assets  
- Limit public employee information  
- Use security headers and hardened configurations  


📂 Each subfolder in this section contains detailed labs with screenshots and step-by-step execution.
