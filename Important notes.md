1. This is version 0.0.1 of the file.
2. This list NOT CONTAINING all tools, just the famous ones that I used.
3. This file containing tools from deferent courses:
	* Certified Ethical Hacking (CEH V9) - Abd Allah Elsokarry  (Arabic version).
	* Certified Ethical Hacking (CEH V12) - EC-council official course.
	* Junior Penetration Tester (eJPT) - INE official course
	* Practical Ethical Hacking (PEH) - Heath Adams as instructor and the CEO of TCM group.
1. Every tool has addition attributes, so use -h next to the tool for more attributes.
2. I'm using KALI Linux, but you can use any system you want.
3. If your device is not a heavy duty one that can endure VM ware -as my device- you can use a windows sub-system for Linux (WLS).

	- WSL default operating system is Ubuntu.
	- If you have already install WSL, write $$wsl --update $$ to update all features.
	- Go to ( [https://kali.org](https://kali.org/) ) and find option to downlead KALI as WSL. Or go to Microsoft store and search for kali Linux and download it.
	- Start KALI WSL.

	> 	NOTE:  KALI WSL is always starting with ROOT USER. That is not good foe beginners, so you need to create new user for you. That can be done by:  
	> 	
	> $$adduser (username_you_want) sudo$$
	> 	Adding a new user and adding the new user into sudo) group.
	> 	It needs password for you user and some more information that you can skip it by using enter button.
	> 		
	> $$su - (username you want)$$
	> 	To change to your user. (BE SURE to add a space before your user)
	> 			
	> $$exit$$
	> 	To return to your root user.
7. Start by updating and Upgrading the system.
8. Start installing your tools.
9. If you want to add GUI for KALI WSL, then GO ON AMD WRITE:

	$$apt install kali-win-kex$$ 
	(use `sudo` if you not using root user)7

	* Start your GUI by:
		  collapsed:: true
			$$kex$$

>    NOTE: Usually, most of KALI VM or WSL have some issues here or there. So you need to fix it.  
>    
