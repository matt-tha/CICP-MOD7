#### Instructions

**Begin on the Impact Pro Client virtual machine.**

1. Launch RPT number 2, Client-side Attack and Penetration
2. Specify helpdesk@doubleshield.org as the From address and dmills@doubleshield.org as the To address. Click Next.
3. Select Single Exploit Attack. Click Next.
4. Select Trojan. Click Next.
5. For this exercise select Not Packed. However take a moment to review the other available options. Click Next. 
6. Select Windows as the target platform. Click Next. 
7. Select Wait Indefinitely for Incoming Connections. Click next. 
8. Continue with the default email template. Click Next.
9. Enter “ mail.doubleshield.org “ as the SMTP Server. Click Next. 
10.Proceed through the remainder of the wizard using default settings.

**Switch to the End User PC virtual machine.**

1. If not already open, launch Outlook Express. 
2. Click the Send/Receive button located on the toolbar. 
3. Double Click to open the newly received email message. 
4. Double Click the attached “ update.exe “ attachment and process to open and install package.
Congratulations. As the end user you have just fallen victim to a Trojan attack. 

**Switch to the Impact Pro Client virtual machine.**

1. To verify the End User PC has been successfully exploited and that an OS Agent has been installed click on the Network tab in the top center of the workspace. 
2. If successful you will now see a network entity for 10.12.4.16, this is the End User PC.
3. If you wish you can now proceed with Network Attack and Penetration as demonstrated in Module 5b. (Practice makes perfect.)

This concludes the lab exercise.

