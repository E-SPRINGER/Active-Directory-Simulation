# Active-Directory-lab

## Create an Active Directory Domain



![Image Alt Text](https://i.ibb.co/8jLNRgP/AD-PROJECT.jpg)




In this project I create an Active Directory Domain
Add multiple users using PowerShell adding a  computer(s) to the domain.  This simulates a corporate environment.

## Technologies and Components Used:


•	Active Directory Domain service

•	Dynamic Name server (DNS)

•	Dynamic Host Configuration Protocol (DHCP)

•	Network Address Translation

•	PowerShell 

•	Oracle Virtual Box

•	Windows server 2019

•	Windows 10 Pro

•	Internet Information Service IIS



I created a VM using virtual box, Installed windows server 2019 ISO. 

![Image Alt Text](https://i.ibb.co/NCW0DTt/ISO-SERVER2019.png)



## The following roles and services for Active Directory and the Domain Controller were configured



•	Active Directory Domain service

•	Dynamic Name server (DNS)

•	Dynamic Host Configuration Protocol (DHCP)

•	Remote Access

•	File and Storage service

•	IIS 


![Image Alt Text](https://i.ibb.co/yN62tfK/Server-roles.png)





on the Left shows how we get to the iternet after joining the domain ,  on the right shows internal network


![Image Alt Text](https://i.ibb.co/wzYF07M/server-netork-adapters.png)




Two custom PowerShell scripts were executed. The first script generated 1000 fictional names. Ultimately, 1,000 users were created within the matter of minutes.



![Image Alt Text](https://i.ibb.co/PMZYt9B/generate-random-names-PS.png)







My name was then placed at the top of the generated file to ensure the next script correctly generated the users (Added an extra r on end of my name 

![Image Alt Text](https://i.ibb.co/RbSKbQD/namestxt.png)




## This PowerShell Script created 1000 user accounts from the generated 


![Image Alt Text](https://i.ibb.co/1vHgCtZ/Create-AD-accounts.png)


## Active Directory accounts created 

![Image Alt Text](https://i.ibb.co/WxYLv0s/Active-Directory.png)


## Joining Windows 10 Pro to the Domain

 An ISO image was used to install the operating system on the VM. The Network Adapter was set to "Internal Network" to ensure all network traffic would only flow through the Domain Controller. On the Windows VM, a local account was created to access the machine. The previously created domain, mydomain.com, was pinged and a connection was verified. The machine was then joined to the domain.

![Image Alt Text](https://i.ibb.co/yq5sf6f/WIN-10-JOINED.png)


![Image Alt Text](https://i.ibb.co/hC8s3cB/WIN-10-iu-dhcp.png)



![Image Alt Text](https://i.ibb.co/sPJBfMg/domain-login.png)












- placehoder (Windows Event Logs)
- placehoder(Linux Event Logs)
- placehoder(Log Analytics Alerts Triggered)
- placehoder(Linux Event Logs)
- placehoder
