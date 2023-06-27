---
layout: single
title:  "The Senior Network Beginnings and Future Plans"
tags:
  - Proxmox
  - Lab
  - Networking
---

During this past junior year, I was given a great opportunity to start the framework and evaluation of the soon-to-be senior network with a fellow classmate. I've always wanted to do hands-on networking projects, beginning with my Proxmox home lab environment. However, with this project, we can implement a solution that teaches both my partner and me the inner workings of a real, small/medium-sized business' internal network.

Our program has always needed an improved network, especially during our Cyberpatriot XV competition. The file transfer speed was extremely slow and it was apparent the program was in need of an upgrade, but we needed knowledgable engineers to do so. As a result, My partner and I stepped in for that role!

After testing our solutions, we were able to improve network speeds, productivity, and learning throughputs by a tremendous amount. Our solution was a huge success in the program and received wonderful acclaim from students and our teacher!

PS: In this blog I will not discuss much about the specfic devices in our network, mostly just solution/ network architecture.

Some of the software we used to troubleshoot and pen-test include:
- Iperf3, certifying network speeds and transmissions
- Nmap, verifying open/ closed ports
- Nessus, detailed scans for our solutions
- Kerbrute, Active Directory kerberos enumeration and testing
- Enum4Linux, enumerating SMB information for our NAS solution
- Wireshark, Discovering device broadcasts and verifying IP address/ DNS queries and requests

### Detailed Information of the Solutions
---

#### Type-1 Hypervisor Backbone

To create an efficient backbone for our network, we needed a manageable and easily expandable solution. So, as a result of my previous knowledge and studies in the field, I settled on the Proxmox Virtualization Environment.

Our Proxmox Environment was installed on 3 Enterprise Servers, and 2 Dell OptiPlex 7070s (for the extra power). With our installations clustered together and Linux PAM users established, we could now easily manage and monitor our environment from anywhere on our school's local network.

Creating and designing specialized Virtual Machines and Containers couldn't have been easier and more secure. It was an absolute game changer that, admittedly, got me very excited with the opportunities we had.


#### Network Storage Solution, TrueNAS

As, naturally, our program needed an extensive file transfer backbone, TrueNAS was a perfect choice for our environment. Offering top-tier managability, speed, and installation, we just could not pass it up.

Our uses for TrueNAS include:
- SMB Cyber Patriot ISO file sharing
- ISO file management/ storage
- NFS share management
- Local document sharing for collaboration
- Local developer documentation storage
- Personalized shares for specific students for personal backups

#### Active Directory Solution

Just about every local network environment contains an Active Directory, And ours does too! Utilizing Windows Server 2022, my fellow engineer and I specially configured the Active Directory for our 30 student Desktops.

Our uses for Active Directory include:
- User and Group management 
- DHCP/ Network Subnet configuration and management
- Local DNS solutions for on-prem Web Servers
- Pre-installed general software
- Student designed Group Policies

#### Logging Solutions

There are many Open-Source logging solutions that work efficiently for a network, however, what worked the best for us was Graylog's solution. Graylog provides us a great central management for system logging and notification management.

Our uses for Graylog include:
- Proxmox login details
- Virtual Machine runtime logging
- Allows our team to diagnose any issues within our network
- Email notification management



### Future Plans for the Senior Network 
---

Due to our limited timeframe, we couldn't implement all of the solutions we wanted to, so we're saving some of these for the next, and last, year in our Cybersecurity program. With my specially crafted schedule, I'll finally have enough time to develop many more solutions, learning materials, and labs for our program.

Students need to learn with lab environments, and our network allows that! The only catch is the limited people-power. My partner and I are only two people, and we shed blood, sweat, and tears to learn as much as we could with our limited time! With the knowledge we have now, I am hoping we can get more student engineers to help us and create new ideas for the program.

Some of the future solutions and labs include:
- Snort SIEM
- Possible Splunk/ ELK SIEM Solution
- Remote Desktop Connection Manager
- SQL Database Website Backend for testing
- Improved Layer 2 -> 3 Network redundancy and speed
- Wireshark/ Switch Port Mirroring
- Open-Source SNMP Solution
- Hyper-V & VMWare ESXi Virtualization Solution
- Locally hosted Steam-cache
- Locally hosted Repository Cache
- Simulated Ethical Hacking lab
- Red Team vs Blue Team lab
- Much, much, more

>Here are images of the network!
>
><img src="{{ site.url }}{{ site.baseurl }}/images/seniornetwork1.jpg" alt="" class="full">



>
><img src="{{ site.url }}{{ site.baseurl }}/images/seniornetwork2.jpg" alt="" class="full">
>