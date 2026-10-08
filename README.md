# home-soc-lab
Home SOC lab with Active Directory, Splunk, and Kali Linux for detecting and investigating attacks
# Home SOC & Active Directory Lab

**Status: In Progress**

## Overview
A home lab that simulates a small corporate network. I use it to practice
IT administration and security monitoring: managing users in Active Directory,
sending logs to Splunk, running attacks from Kali Linux, and detecting them.

## Lab Setup
| Machine | OS | Role |
|---|---|---|
| DC01 | Windows Server 2022 | Domain controller (Active Directory, DNS) |
| CLIENT01 | Windows 11 | Domain-joined user workstation |
| SPLUNK01 | Ubuntu Server | Splunk Enterprise (free) for log collection |
| KALI01 | Kali Linux | Attacker machine |

**Tools:** VirtualBox, Active Directory, Group Policy, Splunk, Splunk Universal Forwarder, Wireshark, Kali Linux

## Progress
- [ ] Install VirtualBox and create VMs
- [ ] Set up Active Directory and DNS on Windows Server
- [ ] Create users, groups, and Group Policies
- [ ] Join Windows 11 client to the domain
- [ ] Install Splunk and forward Windows event logs
- [ ] Run brute-force attack from Kali
- [ ] Detect failed logins (Event ID 4625) in Splunk
- [ ] Build Splunk alert and dashboard
- [ ] Capture and analyze attack traffic in Wireshark

## Screenshots
Coming soon.

## What I Learned
Coming soon.
