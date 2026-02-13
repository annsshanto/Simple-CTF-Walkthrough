## To view without downloading click ➜


# Simple CTF — TryHackMe Walkthrough
<br><br>
This repository documents the full exploitation workflow for the Simple CTF machine on TryHackMe.
The objective is to enumerate exposed services, identify a vulnerable web application, exploit an SQL Injection flaw, gain initial access via SSH, and perform privilege escalation to obtain root access.  


## Overview


The walkthrough follows a standard penetration testing methodology:  

-Reconnaissance & Scanning  
-Web Enumeration  
-Exploitation  
-Credential Cracking  
-Initial Access  
-Privilege Escalation  


## Key Findings  

Open Services:  

-FTP (21)  
-HTTP (80)  
-SSH (2222)  


## Discovered Web Application:  
-CMS Made Simple 2.2.8  


## Vulnerability Identified:  
-CVE-2019-9053  
-SQL Injection (SQLi)  


## Initial Access Method:  
-SQLi exploit → password hash extraction → wordlist cracking  


## Privilege Escalation:  
-Misconfigured sudo permission allowing vim as root  
-Root shell via GTFOBins technique  


## Tools Used  
-Nmap  
-Dirb  
-Python  
-RockYou wordlist  
-SSH  
-GTFOBins  


## Skills Demonstrated  
-Network enumeration  
-Web directory brute-forcing  
-Vulnerability research  
-Exploit execution  
-Password cracking  
-Linux privilege escalation
