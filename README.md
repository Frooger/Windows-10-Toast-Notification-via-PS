# Intro
Powershell Script that create an Windows 10 Toast Notification
based on an XML Layout

# Installation

Execute Install Command File.
IT will create 2 Sample Notifications
in your task scheduling. 

After that copy the PS-Skripte Directory on your 
D: Partition.

Review it:
Task scheduling->run Info-XXX Task
## Create own Notification

### Layout
Create your own Layout XML file based on the sample files in 
Windows-10-Toast-Notification-via-PS/PS-Skripte/PS-Skripte/
### Scheduling Task
Go to task scheduling and create a new task with this action:
#### powershell -file D:\PS-Skripte\Info.ps1 D:\PS-Skripte\Bäcker\Bäcker.xml
and you trigger like everyday 10am
