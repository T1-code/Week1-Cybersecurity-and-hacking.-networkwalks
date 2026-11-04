# Week1-Cybersecurity-and-hacking.-networkwalks
# Week 1: Cybersecurity & Hacking Internship – Lab Setup

## Overview
This repository documents Week 1 of my cybersecurity and hacking internship,
where I built a virtual lab for ethical hacking practice.

## Objectives
- Set up an isolated virtual network
- Install and run Kali Linux as a testing machine
- Verify network connectivity

## Tools & Environment
- Oracle VirtualBox
- Kali Linux (virtual machine)
- Firefox (pre-installed in Kali)

## Setup Steps
### 1. Create a NAT Network in VirtualBox
- Opened VirtualBox Manager > Network > NAT Networks
- Created `NatNetwork` with IPv4 prefix `10.0.0.0/24`
- Enabled DHCP so VMs receive IP addresses automatically

![VirtualBox NAT Network](images/image1.png)

### 2. Launch Kali Linux
- Attached the Kali VM to `NatNetwork` and booted it
- Opened a terminal to confirm the system works

![Kali Linux Desktop](images/image2.png)

### 3. Test Internet Connectivity
- Opened Firefox in Kali and searched "cyber security" on YouTube
- Confirmed the VM can reach the internet through the NAT network

![Kali Firefox](images/image3.png)

## Key Learnings
- How NAT networks isolate lab machines while allowing internet access
- How DHCP assigns IPs inside a virtual network
- Getting started with the Kali Linux environment

## Next Steps
- Run basic network commands (`ip a`, `ping`, `nmap`)
- Add a vulnerable target machine to the lab

## Disclaimer
All activities were performed in an isolated lab for educational purposes only.

## Author
Tapiwanashe Ripondo
