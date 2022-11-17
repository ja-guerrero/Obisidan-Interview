

## **Networking Questions**

#### What is DHCP

- Answer:
	- DHCP stands for Dynamic Host Configuration Protocol. DHCP automatically assigns IP Address to computers, saving us the trouble of having to manually enter and assign an IP Address to a device. The way this works is the client or device sends a DHCP Discover request to the DHCP Server running on the network. The DHCP Server then sends a packet back containing an offer of an ip address which the device needs to accept to gain connectivity 
- Simplified Answer:
	- DHCP is a way for computers to connect to the internet without having to configure as much wifi settings. Without DHCP we would have to enter and assign specific settings like IP address to ensure the device gets connetivity

- Advantages of DHCP
	- Less of a chance two devices share the same IP Address
	- Easy Network configuration, saves a lot of time
	- Devices are able to go from one network to another really important for Mobile Devices



### What is DNS

- Answer :
	- DNS Stands for Domain Name Resolution. It allows devices to resolve domian names like google.com into actual IP address for the network to communitcate to. DNS also goes the other way around and can resolve IP addresses to Domain names as well. If a site is not qualified or known, the default DNS Server will not be able to resolve the IP address. We can edit the devices hosts/ dns profile to manually add a site to it's IP Address or add it to our DNS Server to ensure conenctivity to internal or specific sites.

- Good to know Facts:
	- Mac OS / Linux:
		- Hosts profile can be found at /etc/hosts
		- Can change DNS Servers and Search Domains at Wifi Settings > More Details > DNS
	- Windows: 
		- Hosts profile can be found at Network and Internet > Network & Sharing Center > Change Adapter Settigns > Properties of network > IPv4 > DNS
	
-  Good commands to know for DNS and website troubleshooting:
	- DIG
	- NSLOOKUP










## Story/Behavioral Questions

### A time when you face a Security Issue
-  At my Previous job an exec lost his device which stored a lot of sensitive information about the company. Right away the first thing that came to mind is go to our MDM Product and lock down his device as soon as possible. We had all Mac's File Vaulted so once locked the device could not be entered in anyway without the pin provided from our MDM Solution. After locking his computer I alerte the Security team for further insight and Transparency. We did analysis on logs that came from our MDM Solution on recent activity and made sure there was no login or any attempts of penetrating the system. We then tracked down the system and ensured there was no malware or persistance cracking mechanism on the device 

### How would you solve a networking Issue
- First I would Isolate the issue by trying to find out a few different things
	-  Is it only this user having this issue?
		- If the user is unable to access any sites or network I would first check the user's settings on their device, 
				- Is the wifi connected?
				- Is the DNS Set correctly?
				- Is the device recieving an address for the DHCP Server
			- If all these settings are set correctly I would then check from our network and Server a few different things
				- Is the firewall blocking his traffic access
				- What results do I get from Ping and Tracerout commands
				- Are Packets being dropped?
				- Does the OU or Group have policies blocking further access
	-  Is it just a Specfici website being down or not connecting?
	-  Is it an Org wide issue?









## *General Knowledge Questions*
####  What is MDM
- MDM Stands for Mobile Device Management. It is used to manage mobile endpoints such as MacOS, IOS, TVOS, and Androids. 
- What can an MDM do: 
	- Mobile Managemet
	-  Endpoint Security
	- Application Security
	- IAM (Identity and Acess Management)
	- Device Tracking

### What is the Cloud
- The Cloud is a way to recieve Network, computing,hosting and storage resources through the internet. This is doen through various remote servers. It is highly scalable and secure that it is becoming one of the most needed service out there. Some of the main providers of Cloud Services is Google, Azure, and AWS. These three prodominate the Cloud market because of the great resources they provide 


### What is IAM (Identitity and Access Management)
- IAM Stands fo Idenetitty and Access Management. It is used to authenticate and authorize, users, groups, and devices to specific resources to ensure only authorize people get access to the applications the may need like emails, databases, data, and applications
- Diffent types of Auth:
	- MFA
	- Token
	- Biometric 
	- Credentials (Password Based)
- Different Authentication Methods:
	- Oauth
	- Oauth 2
	- SAML 
	- SSO (Single Sign On)
	- Credentials
	- MFA (MultiFactor Authentication)

### Do you know Linux OS
- Linux is an open source operating system that is Unix Like and uses the Linux Kernel. The linux Kernal is the central part of the linux opertaing System as it is the core interface between hardware and process. Since it is open source it is used for a lot of purposes like Security 



### Questions to Ask:
- What is the current Onboarding And offboarding Process?
- What are some of the future projects you wish to work on or that you have in mind currently?
- What certifications do you find stand out for this field?
- What is your current Documentation flow and process?
- What is communication like between teams?
- What do you like most about this company?
- How much room for growth is there for me if I were to work at this company? 
- 