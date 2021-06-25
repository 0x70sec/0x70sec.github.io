---
title: Certified Red Team Professional Course Review
published: true
---
Attacking and Defending Active directory 

![](https://raw.githubusercontent.com/0x70sec/0x70sec.github.io/master/assets/images/crtp.png)

The importance of Active Directory in an enterprise cannot be stressed enough. Used by more than 90% of Fortune 1000 companies, the all-pervasive AD is the focal point for adversaries. It is used to manage everything from windows servers to applications.Still, when it comes to AD security, there is a large gap of knowledge which security professionals and administrators struggle to fill. Attacking and defending active directory course fills those gaps and builds solid knowledge for both red and blue teamers. CRTP focuses on exploiting misconfigurations in ad environment rather than using exploits.


# [](#header-1)The Course / lab

The course is beginner friendly. It's instructed by Nikhil Mittal, The Developer of the nishang, kautilya and other great tools.So you know you're in the good hands when it comes to Powershell/Active Directory. I took course for 1 month which was more than enough for me, if you spend few hours a day studying and practicing, it should be enough for you as well.
you're given pdf and video materials. Theory, exercises and even walkthroughs. i'd recommend studying theory, and practicing exercises in the lab for each topic without looking into walkthroughs, although if you're stuck, it's okay to see the solutions, just make sure to do exercises multiple times and get all the flags. Try different techniques and different tools (powerview, powerview_dev, ad module, rubeus, mimikatz etc). The lab is stable and accessible both with web and vpn access.It contains approximately 10 machines spread over two forests and various child forests.The course mainly focuses on powershell based tools and exploitation, although you're not limited to using only  these tools. you can use other tools, techniques and c2 frameworks as well. It's great environment to test new tools and techniques. I'd recommend using course material and tools before testing your own. If you are feeling confident try multiple approaches.

 
![](https://raw.githubusercontent.com/0x70sec/0x70sec.github.io/master/assets/images/flags.png)



### [](#header-3)The Exam
The exam consists of five machines, spread over multiple domains. You are given windows student machine credentials, which isn't counted as one. You start as a low privileged user. The goal is to get command execution on all of 5 machines. It's not necessary to get  privileges on every one of them, although it may be required. You can connect with vpn over rdp or choose web access. You're given 24 hours to complete exam and 48 hours to submit a report. Everything on exam is what you practiced in the lab, although it suggests that no cracking is required, so you don't have to worry about some techniques on exam that require cracking wink wink.. Overall I wouldn't say the exam's hard, but it's not one to underestimate. In total it took me 6 hours to complete exam. I continued writing report on the same day and submitted it in approximately 11 hours.
### Tips:
* Enrich the theory
* Practice exercises multiple times in the lab
* Use different tools for enumeration 
* Take Breaks
* Dont overthink 


![](https://raw.githubusercontent.com/0x70sec/0x70sec.github.io/master/assets/images/crtp_verified.png)

### [](#header-4)Summary :
Certified red team professional is the best active directory introduction course for 250$. I'd recommend it to both red and blue teamers. Pentester academy has expert course as well (CRTE), if you are interested in studying AD on more advanced level.

### Resources :
* ![]https://casvancooten.com/posts/2020/10/getting-the-crtp-certification-attacking-and-defending-active-directory-course-review/
* (https://davidhamann.de/2020/12/25/crtp-review-pentester-academy/)
* (https://casvancooten.com/posts/2020/11/windows-active-directory-exploitation-cheat-sheet-and-command-reference/)
* (https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse)
* (https://www.labofapenetrationtester.com/2016/02/getting-domain-admin-with-kerberos-unconstrained-delegation.html)
* (https://adsecurity.org/)



