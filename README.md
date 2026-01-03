# IT Support Helpdesk Lab

## Overview
This project demonstrates hands-on experience in setting up virtual machines and performing real-world Level-1 IT Support troubleshooting tasks using Windows Server and Windows 11.

## Role Simulated
- IT Support Engineer
- Desktop Support (Level 1)

## Tools & Technologies
- Oracle VirtualBox
- VirtualBox Extension Pack
- Windows Server 2022
- Windows 11
- Command Prompt
- VirtualBox Guest Additions

## Lab Environment
- Host OS: Windows
- Virtualization: VirtualBox
- Network Type: NAT

## Tasks Completed

### VirtualBox Setup
- Installed Oracle VirtualBox
- Installed VirtualBox Extension Pack
- Created and configured virtual machines

### Windows Server (Standalone)
- Installed Windows Server 2022
- Fixed login and keyboard issues
- Installed VirtualBox Guest Additions
- Renamed server (DC01)
- Verified system and network functionality

### Windows 11 Client
- Installed Windows 11
- Created local user account (Personal use)
- Resolved no-internet issue
- Installed Guest Additions
- Fixed slow VM performance
- Managed automatic Windows updates
- Resolved display and input issues

## Troubleshooting Performed
- No internet connectivity
- Slow system performance
- Missing network adapter
- Windows update delays
- Screen resolution issues
- Keyboard and mouse capture problems

## Challenges Faced
- Windows 11 forced updates causing long delays
- VM running slow due to low RAM and CPU
- Network adapter not detected initially
- enable virtualization
- Internet access blocked during Windows setup

## Solutions Implemented
- Increased VM RAM and processor cores
- Installed VirtualBox Guest Additions
- Adjusted network adapter settings
- Used local account instead of Microsoft account
- Followed systematic troubleshooting approach

## Commands Used
ipconfig
taskmgr
chkdsk
sfc /scannow
services.msc
VBoxWindowsAdditions.exe
