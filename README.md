# Basic Network Scanning with Nmap

## Internship Information

Organization: Oasis Infobyte

Program: Cybersecurity Analyst Internship (OIB-SIP)

Task Number: 1

Task Title: Basic Network Scanning with Nmap

## Objective

Perform a basic network scan on a local Windows machine using Nmap to identify open TCP ports and running services. Analyze the identified services and explain their significance.

## Tools Used

- Nmap 7.99
- Microsoft Windows 11
- Command Prompt

## Steps Performed

1. Installed Nmap.
2. Verified installation using:
   nmap.exe --version
3. Checked local IP using:
   ipconfig
4. Performed a basic scan:
   nmap.exe -Pn 192.168.1.153
5. Performed service detection:
   nmap.exe -Pn -sV 192.168.1.153
6. Saved output to nmap_scan_results.txt.

## Scan Results

| Port | State | Service |
|------|-------|---------|
|135|Open|MSRPC|
|139|Open|NetBIOS-SSN|
|445|Open|Microsoft-DS|

## Outcome

Successfully identified open ports and running services on the local Windows machine using Nmap.

## Repository Contents

- README.md
- nmap_scan_results.txt
- screenshots/
- demo/

## Author

Sabina Akter
Cybersecurity Analyst Intern
Oasis Infobyte (OIB-SIP)
