# Task Five - Metasploitable Nmap Scan Results

## Introduction

This repository contains the results of an **Nmap** scan performed on a **Metasploitable2** virtual machine. The scan aims to identify all open ports and services running on the system, which is a deliberately vulnerable virtual machine used for security testing and penetration testing practice.

## Metasploitable2

Metasploitable2 is an intentionally vulnerable virtual machine that provides a safe environment for testing security tools and techniques. It contains several vulnerable services and configurations that mimic real-world attack vectors.

### Nmap Scan Overview

The **Nmap** scan was performed with the following parameters:
- **All Ports Scanned**: 0-65535
- **Service and Version Detection**: Using the `-A` flag
- **Output**: Results saved in a text file format

### Nmap Command Used

```
nmap -p- -A [Metasploitable_IP] -oN metasploitable_scan.txt
```
-p-: Scans all 65535 TCP ports.
-A: Enables OS detection, version detection, script scanning, and traceroute.
-oN: Saves the output in a human-readable format.

### Installation and Setup

To replicate this scan, follow the steps below:
``
  Install Metasploitable2:
  Download from SourceForge.
  Set up the VM using VMware or VirtualBox.

   Run the Nmap Scan:
   Ensure your Kali Linux or Nmap tool is installed.
   Use the command provided above to perform the scan on the Metasploitable2 VM.

  Save the Results:
  Output the results into a text file for future reference.


  
