# Securing-a-Linux-Server-in-Azure-Cloud
## Overview
In this lab, I created a Linux virtual server in Microsoft Azure and took steps to make it more secure. The goal was to learn how cloud servers work and how to protect them from common security risks.

I set up safe user access, limited how the server can be accessed remotely, reviewed what was running on the system, and added basic network protections. I also made sure the server receives security updates automatically.

This project highlights my growing experience with cloud technology, Linux systems, and cybersecurity as I work toward a Bachelor’s degree in Cloud and Network Engineering.

## Lab Walkthrough

## This screenshot shows the Linux virtual machine successfully created in Microsoft Azure, confirming the cloud environment used for this lab.
![Completed SSH into Linux Azure Cloud](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/4534524dd90528d5c628ec420c673ecf1a5e8882/completed%20linux%20os%20ssh.png)
## A non-root user was created to manage the server. The user was granted administrative privileges using the sudo group permission access, allowing system management while maintaining accountability and security.
![Sudo User Creation](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/67980f0298e849ffb783e0866e02983f45d2e1bc/kimmie.png)
## Added a user with no sudo priviledge rights 
![Add user cole](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/4f3ea648dcd27131909c44d4cadd6049b196e82c/cole.png.png)
![No sudo privileges for user cole](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/d2d25a97cec28b48a8081c018a9f5518de586948/nonsudousercole.png)
## Key-based authentication was configured to provide a more secure method of logging into the server than passwords alone.
![SSH Connection](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/85648293ccf5c29937aeb79aa889c3fcf02ec5be/ssh.png)
## The firewall was enabled and configured to allow only necessary network traffic, helping protect the server from unwanted connections.
![UFW Firewall Enabled](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/d4edf55dfd061d3f2fb47900e3da6bb18ed909c8/ufw.png)
## Running system services were reviewed to identify and evaluate processes that could increase the server’s attack surface.
![Running Services](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/2eea4a6bee21d6753d8ad8a38dc5e90fc1a548b9/services.png)
## Unneeded system services were identified and disabled to reduce the server’s attack surface and limit potential security risks.
![Disable Services](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/02e83b798ab43cc2f4d0d5aa70bb309f14f679dc/diableservices.png)
## The server was checked for updates and autoupdates were enabled to ensure the system regularly receives important security patches.
![Update server](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/4c5feadfc52a43750be12684a52686d46975b9eb/updates.png)
![Add autoupdates](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/71fca31af9509cc1bee7f7837c92ef322d685072/addautoupdate.png)
## System login records were checked to verify that access to the Linux server is occurring as expected and without suspicious activity.
![log activity of Linux Server](https://github.com/zcooley00/Securing-a-Linux-Server-in-Azure-Cloud/blob/a707aa9d66dfb5900631b31075c00c2a2462c477/log.png)
