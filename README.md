# WEEK 2 – FOOTPRINTING & NETWORK SCANNING (NetworkWalks Cybersecurity Internship)

# Summary of the Week 2 project modules:

Reconnaissance against a target domain using multiple Kali tools, theHarvester, and Zenmap.
 
 # 📌 W2-PM1: Footprinting with Multiple Kali Tools

# Objective
Gather public information about the target domain using a range of command-line and GUI recon tools.

# Tools Used
WHOIS – domain registration details  	whatweb – identifies technologies/CMS running on the site  	

nslookup – resolves DNS records

curl -I – pulls HTTP response headers wafw00f – detects presence of a Web Application Firewall  	

dnsrecon – enumerates DNS records and subdomains

# Evidence

01_WHOIS.jpg 

02_whatweb.jpg 

03_nslookup.jpg 

04_dnsrecon.jpg 

05_curl.jpg 

06_wafw00f.jpg 


# Key Takeaways

Each tool surfaces a different slice of public-facing information — combining WHOIS, DNS, and HTTPlevel recon builds a much fuller picture of the target than any single tool alone.
 

# 📌 W2-PM4: THEHARVESTER BASED FOOTPRINTING

# Objective

Use theHarvester to collect OSINT data — subdomains, email addresses, and related infrastructure — from public sources.

# Evidence

07_theHarvester.jpg

# Key Takeaways

OSINT harvesting shows how much attacker-useful information (emails, subdomains) is already public before any active scanning begins.
 
# 📌 W2-PM5: ZENMAP BASED NETWORK SCANNING

# Objective

Use Zenmap (Nmap's GUI) to scan the target for open ports, live hosts, and network topology.

# Evidence

01_Nmap scanning.jpg 

02_Nmap topology.jpg

# Key Takeaways

Zenmap's visual topology view makes it easier to map out the attack surface at a glance compared to reading raw Nmap CLI output.
 

# 📄 Full Report

See W2-PM-FINAL - AdebayoJudith Report for the complete write-up covering all modules above.

# 🙏 Credit
NetworkWalks Academy | Cybersecurity & Ethical
Hacking with AI — internship led by Waqas Karim.
