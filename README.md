## Bootable USB Toolkit

## About
Created a multi-tool bootable USB that supports system recovery, memory testing, virus and malware detection, password resetting, secure file deletion, and forensic diagnostics. Proper for scenarios where the main OS cannot boot or when user permissions are restricted on the computer.

 Bootable USB Toolkit for Emergency System Recovery & Diagnostics

## Overview

This project demonstrates the creation of a multi-boot USB drive containing a variety of open-source tools for system diagnostics, malware removal, data recovery, password resetting, secure wiping, and penetration testing. The USB was built using [YUMI](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/) and is intended for use in IT support, cybersecurity, or digital forensics environments.

This project was completed for an IT Infrastructure course final project.

## Tools Included

Tool 
Purpose 
Use Case
Kali Linux
Penetration testing and ethical hacking
 Run recon, network scans, and password testing on target systems 
Dr. Web Live Disk
Bootable antivirus
Scan and clean malware from systems that won’t boot
Rescatux
Boot and Password Recovery
Reset Windows/Linux user passwords, fix GRUB, restore MBR
MemTest86
RAM Diagnostics
Detect faulty memory modules that cause crashes or instability
SystemRescueCD
Linux-based recovery environment 
Access files, repair partitions, run disk tools on damaged systems 
ShredOS
Secure data erasure
Permanently wipe drives using DoD-standard deletion algorithms 



## Portable Windows Apps (for use without admin privileges)

Installed via [PortableApps](https://portableapps.com/):
ClamWin: Antivirus scanning tool
Spybot Search & Destroy: Spyware and malware cleaner
KeePass Professional: Password manager
Firefox: Web browser
Notepad++: Code and log file editor

These tools can be launched on any Windows machine directly from the USB without requiring installation.


## How I Built The Tool

1. Downloaded YUMI from the official site
2. Downloaded ISO files for each bootable tool from their respective sites
3. Used YUMI to add each ISO to the USB (MultiBoot mode)
4. Installed the PortableApps platform and added essential apps
5. Tested the USB on multiple machines for compatibility and tool access


Due to system limitations, screenshots of the boot menu cannot be taken while the system is off. However, the YUMI bootloader successfully displays all added tools, with a custom splash screen that includes my name for project identification.


## Example Uses 

System won’t boot?
  → Boot into SystemRescueCD or Dr.Web to recover files or run antivirus scans.

Locked out of a computer? 
  → Use Rescatux to reset the password and regain access.

Suspect faulty hardware? 
  → Run MemTest86 to identify memory issues.

 Need to destroy sensitive data? 
  → Boot into ShredOS to permanently wipe drives.

Need admin tools on a locked-down system? 
  → Use Firefox, ClamWin, or Notepad++ from PortableApps without installing anything.

## Key takeaways 
This USB toolkit was created as a learning exercise in cybersecurity preparedness, disaster response, and system recovery. It serves as a starting point for IT students and professional pursuing careers in cybersecurity, digital forensics, or network administration.


