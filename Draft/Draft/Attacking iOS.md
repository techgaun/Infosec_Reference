##Attacking & Defending iOS




[Hacking Your Way Up The Mobile Stack](http://vimeo.com/51270090)



CULL



https://www.owasp.org/index.php/Mobile_Jailbreaking_Cheat_Sheet

[MEMSCAN - Dump iPhone app RAM](http://www.cigital.com/justice-league-blog/2015/02/18/memscan-defined/)
* A Cigital consultant � Grant Douglas, recently created a utility called MEMSCAN which enables users to dump the memory contents of a given iPhone app. Dumping the memory contents of a process proves to be a useful technique in identifying keys and credentials in memory. Using the utility, users are able to recover keys or secrets that are statically protected within the application but are less protected at runtime. Users can also use the utility to verify that keys and credentials are appropriately disposed of after use.



iPwn  Apps
:
Pentesting  iOS  Applications
https://www.sans.org/reading-room/whitepapers/testing/ipwn-apps-pentesting-ios-applications-34577


[Bypassing SSL Cert Pinning in iOS](http://chargen.matasano.com/chargen/2015/1/6/bypassing-openssl-certificate-pinning-in-ios-apps.html)

http://project-imas.github.io/

https://www.owasp.org/index.php/IOS_Application_Security_Testing_Cheat_Sheet 	

[idb](https://github.com/dmayer/idb)
* idb is a tool to simplify some common tasks for iOS pentesting and research. Originally there was a command line version of the tool, but it is no longer under development so you should get the GUI version.



http://matasano.com/research/Introducing_idb_-_Simplified_Blackbox_iOS_App_Pentesting.pdf


https://github.com/dmayer/idb
gidb is a tool to simplify some common tasks for iOS pentesting and research. It is still a work in progress but already provides a bunch of (hopefully) useful commands. The goal was to provide all (or most) functionality for both, iDevices and the iOS simulator. For this, a lot is abstracted internally to make it work transparently for both environments. Although recently the focus has been more on supporting devices.
http://cysec.org/blog/2014/01/23/idb-ios-research-slash-pentesting-tool/

http://www.pentesteracademy.com/course?id=2
This course focuses on the iOS platform and application security and is ideal for pentesters, researchers and the casual iOS enthusiast who would like to dive deep and understand how to analyze and systematically audit applications on this platform using a variety of bleeding edge tools and techniques.



###Vulnerabilities/Exploits
List of iOS Exploits:
http://theiphonewiki.com/wiki/Category:Exploits


###Techniques



###Training & Tutorials

Learning iOS Application Security - 34 part series
	http://damnvulnerableiosapp.com/#learn

Damn Vulnerable iOS App
	iOS app designed to be vulnerable in specific ways to teach security testing of iOS applications.
	http://damnvulnerableiosapp.com/2013/12/get-started/

OWASP iGOAT	
	From: https://www.owasp.org/index.php/OWASP_iGoat_Project
	�iGoat is a safe environment where iOS developers can learn about the major security pitfalls they face as well as how to avoid them. It is made up of a series of lessons that each teach a single (but vital) security lesson.�
	https://www.owasp.org/index.php/OWASP_iGoat_Project
	

###iOS Security Testing Methodologies




###General Research Papers




###Reverse Engineering



[IOS Reverse Engineering toolkit](https://github.com/S3Jensen/iRET)
* The iOS Reverse Engineering Toolkit is a toolkit designed to automate many of the common tasks associated with iOS penetration testing. It automates a many common tasks including: 
binary analysis using otool
keychain analysis using keychain_dumper
reading database content using sqlite
reading log and plist files
binary decryption using dumpdecrypted
dumping binary headers using class_dump_z
creating, editing, installing theos tweaks



###Jailbreaking

####Jailbreaking Pros - Cons
	
Guide to hardening iOS with the goal of privacy:
	http://cydia.radare.org/sec/




[IPhoneDevWiki](http://iphonedevwiki.net/index.php/Main_Page)
* �Our goal is to share the sum of all human[1] knowledge about jailbroken iOS development. In other words, this is a collection of documentation written by developers to help each other write extensions (tweaks) for jailbroken iOS, and you're invited to learn from it and contribute to it too.� 



[The iPhone Wiki](http://theiphonewiki.com/wiki/Main_Page)
* The iPhone Wiki is an unofficial wiki dedicated to collecting, storing and providing information on the internals of Apple's amazing iDevices. We hope to pass this information on to the next generation of hackers so that they can go forth into their forebears' footsteps and break the ridiculous bonds Apple has put on their amazing mobile devices. 



###Defeating iOS cryptography







