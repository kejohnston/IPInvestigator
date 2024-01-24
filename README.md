# IPInvestigator
Python driven scripts to help with performing network attack surface

## Purpose
These scripts are intended to provide some automation to external IP and port exposure. The idea is users will have an IP **that they own** which requires some reconaissance against to understand potential threat vectors against that IP. Users would input the IP into IPInvestigator and it would provide important details such as a port scan, results from Shodan/Censys/other tools, and DNS records to provide the user with ample information to make decisions about securing external exposure.

## Roadmap
This is being written before any code to allow for code structure and planning.

### Script Requirements
Take an IP as an input variable, inject the variable into several functions which provide details on:
- Whois
- Reverse DNS
- Port Information (Nmap)

