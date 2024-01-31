# IPInvestigator
Python driven scripts to help with performing network attack surface

## Purpose
These scripts are intended to provide some automation to external IP and port exposure. The idea is users will have an IP **that they own** which requires some reconaissance against to understand potential threat vectors against that IP. Users would input the IP into IPInvestigator and it would provide important details such as a port scan, results from Shodan/Censys/other tools, and DNS records to provide the user with ample information to make decisions about securing external exposure.

This script does utilize 3 python libraries which are found on pypi but included in the repo:
- python-nmap
- python-whois
- pydig

The tool is meant to provide base level investigation to provide a path to further investigation. You will provide an IP and that's it. Originally the tool was going to allow additional input, but simplicity was more important than potential features at least in the initial iteration.

### Script Requirements
Take an IP as an input variable, inject the variable into several functions which provide details on:
- Port Information (Nmap)
- Whois
- Reverse DNS

## Roadmap
In the future the script could be expanded to allow for more user interation, allowing users to specify syntax, and to provide a more robust investigation of an IP address.
