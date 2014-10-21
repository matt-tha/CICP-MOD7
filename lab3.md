#### Instructions

1. Launch RPT number 2, Client-side Attack and Penetration
2. Specify helpdesk@doubleshield.org as the From address and dmills@doubleshield.org as the To address. Click Next.
3. Select Phishing attack. Click Next.
4. On the Phishing Type Selection select Web Page Redirect and leave the default URL in place. This lab does not have external network access, this URL will not be contacted. Click Next. 
5. Click “Change….” to modify the email template for this attack. 
6. Change line 7 to read “ This is an urgent message from the Doubleshield helpdesk”.
7. Click Ok to save the change and click next. 
8. Specify “ mail.doubleshield.org “ as the SMTP server. 
9. Proceed through the remainder of the wizard using default settings. 

**Switch to the End User PC virtual machine.**

1. Login with username “ Debra Mills “ and password “ password123 “
2. Launch Outlook Express from the Desktop. 
3. Outlook Express should automatically download any available email, if it has not click the Send and Receive button from the toolbar. If you did not receive the email message return to Impact Pro and verify your RPT settings. 
4. If you have received the email message single click to open it in the reading pane. Notice your customization of the first line. 
5. Click the hyperlink at the bottom of the email message. Congratulations, as the end user you have just fallen victim to the Phishing attack. A browser will open and data will be sent back to Impact Pro. 

**Switch to the Impact Pro Client virtual machine.**

1. Within the Executed Modules pane expand Client-side Attack and Penetration, and then expand Client-side phishing. 
2. Click on CS-WBA Browser Fingerprint and observe the information collected from the End User PCs browser. 
3. To manually stop the running modules right click Client-side Attack and Penetration and select Stop

This concludes lab exercise 3, continue to exercise 4.
