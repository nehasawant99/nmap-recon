# Nmap Service Enumeration Lab

## Overview

This project demonstrates basic network reconnaissance and service enumeration using Nmap. The objective was to identify open ports, running services, and network exposure on an authorized testing target.

## Tools Used

* Nmap
* macOS Terminal

## Target

* scanme.nmap.org (Official Nmap testing host)

## Command Used

```bash
nmap -sV scanme.nmap.org
```

## What This Scan Does

* Discovers open ports
* Identifies running services
* Detects service versions
* Provides basic network reconnaissance information

## Key Findings

* Port 22 (SSH) was open
* Port 80 (HTTP) was open
* Port 9929 (Nping Echo) was open
* Several ports were filtered by firewall rules

## Skills Demonstrated

* Network Reconnaissance
* Service Enumeration
* Port Scanning
* Basic Security Analysis
* Report Writing

## Files Included

* findings.md
* report.xml
* screenshots/

## Disclaimer

This scan was performed against an authorized public testing target provided by the Nmap project. No unauthorized systems were scanned.
