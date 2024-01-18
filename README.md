# Active-Directory-lab

## Introduction


![Image Alt Text](https://i.ibb.co/8jLNRgP/AD-PROJECT.jpg)




In this project I create an Active Directory Domain
Add multiple users using PowerShell adding a  computer(s) to the domain.  This simulates a corporate environment.

Technologies used.


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



The following roles and services for Active Directory and the Domain Controller were configured



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



- placehoder (Windows Event Logs)
- placehoder(Linux Event Logs)
- placehoder(Log Analytics Alerts Triggered)
- placehoder(Linux Event Logs)
- placehoder
