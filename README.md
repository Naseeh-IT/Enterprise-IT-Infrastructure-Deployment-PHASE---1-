# Enterprise-IT-Infrastructure-Deployment-PHASE---1-
Windows Server 2022 – Domain Controller Setup (VMware Workstation Pro) &amp; Client PC 

Server (DC1)
Windows Server 2022 installed

IP: 192.168.1.10

Domain: Gulfbay.com

NetBIOS: GULFBAY

DHCP Configuration

Scope: 192.168.1.11–192.168.1.100

Excluded: 10,20,30,40,50,60,70,80,90,100

Organizational Units & Users

HR Department → Arun Kumar

Purchase Department → Saleem

Sales Department

Client PC

Client A successfully joined to the domain

Group Policies Applied

Minimum password length: 12

Maximum password age: 60 days

Password history: 5

Account lockout threshold: 5 attempts

Lockout/reset: 15 minutes

Screen lock after 10 minutes

Disabled: Control Panel, CMD, PowerShell, Registry

LAN Segment Configuration

Created internal LAN segment for all servers and client PCs

Ensures isolated communication within the virtual environment

Additional Work Completed

Installed VMware Tools

Created VM snapshots

Verified DNS

Scheduled AD backups
