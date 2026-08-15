# Windows Fundamentals - Day 1

## Objective

Today I explored the Windows operating system and learned the purpose of common Windows tools used by Level 1 IT Support Technicians.

---

# File Explorer

## This PC

Purpose:

What I learned:

Can a normal user safely modify files here?

---

## Local Disk (C:)

Purpose:

What I learned:

Can a normal user safely modify files here?

---

## Windows Folder

Purpose: This is where all the Windows files are kept and it is very crucial for runnng windows

What I learned: These files are to be handled with great importance. 

Can a normal user safely modify files here?
No. If they are deleted then windows may stop working. 
---

## Program Files

Purpose:This is showing all the installed applications on the computer. It keeps the apps and its related features in folder form

What I learned:

Can a normal user safely modify files here?

---

## Program Files (x86)

Purpose: This seperated the older versions of softwares that are installed on the computer. Normally, these programs are the 32 bit versions. These prevent conflict between software from overwriting each other. 

What I learned:

Can a normal user safely modify files here? 

---

## Users Folder

Purpose: This shows the profiles of the users of the computer and the files they have access to. There is a default Public account which can be accessed by anyone but it has limited files as compared to other users. 

What I learned:

Can a normal user safely modify files here?

---

# Windows Tools

## Task Manager

Purpose: It shows each resource that is active an how much resources it is using to run that process. 

Where I found it: I searched from the Start menu.

What I observed: I observed that this tool shows the performance, app history, startup processes and the users. It shows which resources are being used and how much for each process. It can be used to end a process if it there's an issue or disable a startup process. 

My laptop has:
CPU :13th Gen Intel(R) Core(TM) i5-1334U
Memory: 16.0 GV DDR4
Disk: Disk 0 (C:) NVMe P0221 NVMe Phison 512GB
Ethernet:	VirtualBox Host-Only Ethernet Adapter
Wi-Fi: Realtek RTL8852BE WiFi 6 802.11ax PCIe Adapter
GPU: Intel(R) Iris(R) Xe Graphics

Under Startup programs I noticed that a lot of apps were enab,ed on my compputer which can potentially increase my start up time and consume resources in the background so I disabled them. For instance: Opera browser was starting up everytime I start my computer which was uncessary for me because I do not use it as my browser. It was also anoting for me in a way seeing the opera window pop on my screen everytime I switch my computer on when I almost never use the application. 

---

## Device Manager

Purpose: This shows the devices and the drives that are connected to the computer system. 

Where I found it: I searched at the Start menu

What I observed: It categorises devices eg Camera and under it there will be all the available camera options. When you click on a particular drive you can have options like updating, disabling or uninstalling the device which will help for troubleshooting device related programs. 
 I also observed that if you click on a particular let's say camera it will give you all information in regards to it, all details. For instance in the picture belo, I selected a camera and under details I can view the status if the camer, when It was installed, its last update and many more details. 
 <img width="978" height="716" alt="image" src="https://github.com/user-attachments/assets/93ad6a66-3c57-4221-beb6-92d7c8b1c4b3" />

I also observed that if you go to events option, it will show you the events and if you click on view more it will redirect you to event manager where it will be added on custom views. 

 
---

## Disk Management

Purpose: It shows you the number of disks you have on the computer. It also shows the partitions of each disk. It also displays file system eg NTFS, status, capacity and the available space. 

Where I found it:I simply searched on the Start menu. 

What I observed:I observed that when you click on a particular disk, it will show you options to delete or view properties of a particular disk partition. You can also open and view it's content. On my computer I have 5 disk partitions including OS(C:) which uses the NTFS and has the largest capacity at 454.98 GB which is high compared to the other partitions because it is the main storage space for my computer holding system files, user data, applications etc. 

---

## Event Viewer

Purpose: Basically it displays all the activities that have happened on the computer. 

Where I found it:I searched it on the Start Menu

What I observed: I observed that when I expanded the Windows Logs I had logs that were categorised into 4 majr groups namely; Application, Security, Setup, System and Forwarded Events. It also shows some administrative events which show warnings or errors that have occured. An example was, When I clicked on Application, it gave me alist of all the logs including the level, date and time, source and event Id. When a particular log was clicked, event detailed were displayed. They showed what the vent was in both friendly views and XML views. <img width="1902" height="1006" alt="image" src="https://github.com/user-attachments/assets/d3931310-6d50-4eaa-a850-c838ad9aabf5" />


---

## Computer Management

Purpose: This basically shows you the system tools, storage and sevices and applications that are available on your computer. 

Where I found it:I searched it on the Start Menu

What I observed: I saw that whe I click on system tools other tools like event viewer and event manager can be found here without event seacrhing them on the Start menu. I also noted that shared folders can be seen here. I also noted that there is a task scheduler which can be utilized when you want to automate a task. 

---

## Services

Purpose: They are programs that run in the background and ensure that core system tasks are handled correctly like security and network.

Where I found it: I seerached from the Start Menu

What I observed: The list of services is provided and a description of each service is give. A service can be started, restarted, stopped or paused.

---
---

## Drivers

Purpose: They are there to connect Windows to communicate with the hardware. 

What I observed: The drivers are for specific components. Foe example network driver will focus on the connection to network, so here you will see Wi-Fi drivers and Ethernet drivers. This are essential when there is a problem. They give you status and details of the drives whil=cj helps in troubleshooting. They need to be updated accordingly to have the best. xe3

---


## Nwtworking Tools

Command Prompt
Purpose: It is a text uxser interface for navigating and manipulating the computer files, checking and fixing network issues and automating processes etc.
What I observed: When I run "Ipconfig" I am able to view essential nrtworking data like : Address. . . . . . . . . . . : 10.0.0.144
Subnet Mask . . . . . . . . . . . : 255.255.255.0
Default Gateway . . . . . . . . . : 10.0.0.138
I also tried doing "ping" and this is what happened:

C:\Users\lkusi>ping 127.0.0.1

Pinging 127.0.0.1 with 32 bytes of data:
Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
Reply from 127.0.0.1: bytes=32 time<1ms TTL=128
Reply from 127.0.0.1: bytes=32 time<1ms TTL=128

Ping statistics for 127.0.0.1:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 0ms, Maximum = 0ms, Average = 0ms
    
I also tried "nslooup google.com" and this is what happened:
C:\Users\lkusi>nslookup google.com
Server:  mygateway
Address:  10.0.0.138

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4013:407::71
          2404:6800:4013:407::8b
          2404:6800:4013:407::64
          2404:6800:4013:407::65
          192.178.188.101
          192.178.188.138
          192.178.188.100
          192.178.188.113
          192.178.188.139
          192.178.188.102

---

# Reflection

I learned: For me to be able to troubleshoot and work effectienly with my Windows operating system, I need to farmilialise myself with the Windows operations, tools and services. 

Questions I still have:
