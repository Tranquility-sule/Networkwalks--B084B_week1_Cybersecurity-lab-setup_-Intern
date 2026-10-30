# WK1-NetworkWalks: Cybersecurity Lab Setup Using VirtualBox and Kali Linux

## Project Overview

This project focuses on setting up a virtual cybersecurity testing lab environment using Oracle VirtualBox and Kali Linux.

The purpose of this lab is to establish a controlled environment for cybersecurity practical exercises, ethical hacking, network testing and future security-related tasks.

## Project Objectives

The objectives of this project are to:

- Install and configure Oracle VirtualBox.
- Create a custom NAT Network using the `10.0.0.0/24` subnet.
- Download and import Kali Linux into VirtualBox.
- Configure Kali Linux with a static IP address of `10.0.0.2/24`.
- Enable clipboard sharing and drag-and-drop functionality.
- Configure a shared folder between the host operating system and Kali Linux.
- Establish full internet connectivity within the Kali Linux virtual machine.
- Take a snapshot of the configured virtual machine.

## Tools and Technologies

| Tool | Purpose |
| Oracle VirtualBox | Virtualisation platform |
| Kali Linux | Cybersecurity testing and penetration testing environment |
| 7-Zip | File extraction and archive management |
| NAT Network | Virtual network configuration |
| Windows | Host operating system |

## Lab Network Configuration

The following network configuration was specified for the lab:

| Configuration | Value |
|---|---|
| Network Type | NAT Network |
| Network Subnet | `10.0.0.0/24` |
| Kali Linux IP Address | `10.0.0.2/24` |
| Gateway | `10.0.0.1` (if required) |
| Internet Access | Enabled |

## Implementation Steps

### Phase 1: Basic Lab Setup

1. Downloaded and installed 7-Zip.
2. Downloaded and installed Oracle VirtualBox.
3. Created a custom NAT Network with the `10.0.0.0/24` subnet.
4. Downloaded and imported the Kali Linux virtual machine.
5. Configured the Kali Linux network interface with the required IP address.
6. Configured clipboard sharing and drag-and-drop.
7. Enabled the shared folder for the host's `/downloads` directory.
8. Configured and tested internet connectivity.
9. Created a snapshot of the configured Kali Linux virtual machine.

### Phase 2: Future Optional Tasks

The following activities are optional extensions for future practical exercises:

- Installing additional virtual machines, including Windows 10/11, Windows 7, Windows Server 2016 and Android.
- Configuring the virtual machines on the same NAT Network.
- Performing connectivity tests between virtual machines using ping.
- Taking snapshots of the additional virtual machines.

## Project Evidence

Screenshots documenting the lab setup and configurations are available in this repository.

The evidence covers:

- VirtualBox installation.
- NAT Network configuration.
- Kali Linux virtual machine setup.
- IP address configuration.
- Clipboard and drag-and-drop settings.
- Shared folder configuration.
- Internet connectivity verification.
- Virtual machine snapshot.

## Learning Outcomes

Through this project, I gained practical experience in:

- Virtualisation and virtual machine management.
- Linux operating system installation and configuration.
- Network addressing and subnet configuration.
- NAT Network setup.
- Host-to-guest file sharing.
- Basic cybersecurity lab preparation.

## Project Status

Week 1 – Project Module 1: Completed.

This lab environment provides a foundation for subsequent cybersecurity practical exercises and ethical hacking activities.


Project: WK1 
Focus: Cybersecurity Lab Setup  
Platform: Oracle VirtualBox  
Operating System: Kali Linux
