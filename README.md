# it-homelab-portfolio
This repository documents hands-on IT and cybersecurity projects completed to develop
practical experience with Linux systems, networking, storage, and basic network security.

The focus of these projects is understanding how systems are installed, configured,
secured, and troubleshoot in real-world environments.

## Lab Environment

- Virtualization: VirtualBox
- Operating Systems: Ubuntu Linux, TrueNAS
- Network Services: DNS-based filtering (Pi-hole)
- Hardware: Repurposed legacy laptop for NAS deployment

## Linux Virtual Machine (Ubuntu)

**Objective:**  
Gain hands-on experience with Linux system administration, command-line workflows and virtualization software.

**What I Did**
- Installed Ubuntu in a virtualized environment
- Navigated and managed the system entirely via the Linux command line
- Created and managed users, permissions, and system updates

**Challenges & Troubleshooting**
- Resolved networking configuration issues within the VM
- Learned to diagnose package and dependency errors during updates

**Key Takeaways**
- Improved comfort working in a CLI-only environment
- Gained foundational Linux skills relevant to servers and security tools
  

## Pi-hole DNS Filtering

**Objective:**  
Improve network security and visibility by implementing DNS-level filtering.

**What I Did**
- Deployed Pi-hole as a network-wide DNS resolver
- Configured router DNS settings to enforce filtering
- Reviewed DNS query logs to understand device-level network behavior

**Challenges & Troubleshooting**
- Resolved DNS conflicts with existing router settings
- Tuned filtering rules to balance usability and security

**Key Takeaways**
- Deeper understanding of DNS and its role in network security
- Exposure to monitoring and analyzing network activity
  

## TrueNAS Network-Attached Storage

**Objective:**  
Repurpose older hardware into a functional network storage solution.

**What I Did**
- Installed TrueNAS on bare-metal hardware
- Configured storage pools and datasets
- Set up user permissions for controlled network access

**Challenges & Troubleshooting**
- Learned disk and boot configuration during OS installation
- Adjusted permissions to prevent unauthorized access

**Key Takeaways**
- Experience installing an OS outside of a virtual environment
- Practical understanding of storage management and access control
