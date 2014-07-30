﻿=== WP Mail Bank - PHP & SMTP Mailer ===
Contributors: contact-banker
Tags: admin, email, gmail, mail, mail smtp, Mailer, outgoing mail, phpmailer, plugin, Post, posts, privacy, security, sendmail, smtp, ssl, tls, wordpress smtp, wp smtp, wp-phpmailer, wp_mail
Requires at least: 2.7
Tested up to: 3.9.1
Stable tag: 1.0

WP Mail Bank reconfigures the wp_mail() function and make it more enhanced.

== Description ==

### WordPress Mail Bank - Best PHP & SMTP Mailer

This plugin reconfigures the wp_mail() function nd make it more enhanced to use SMTP instead of mail() with various options available.


###IMPORTANT: If you think you found a bug in WP Mail Bank or have any problem or question concerning WP Mail Bank, do not hesitate to contact us at [support@tech-banker.com](mailto:support@tech-banker.com).  


###Key Features :

* Specify the From Name that emails should be sent from.
* Specify the Email Address that emails should be sent from.
* Specify Transporder to be used for sending out email i.e SMTP or Php mail() function.
* Specify Return Path of your Email or Keep it same as your email address.
* Specify Word Wrap at which the string will be wrapped in email per line.
* Specify SMTP Host to be used for sending your emails.
* Specify SMTP Port to be used for sending your emails. 
* Specify an SMTP username and password.
* Specify Encryption type.
* Specify to use Authentication or disable Authentication.
* Specify SMTP Keep Alive to keep SMTP Authentication Session open or closed after sending emails.


> #### ** Default SMTP Ports & Settings **
> * SMTP Server  - Non-Encrypted - Port 25 ( or 587 )
> * SMTP Server  - Secure (TLS) - Port 587 
> * SMTP Server  - Secure (SSL) - Port 465 

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Googlemail - Gmail SMTP Ports & Settings **
> * SMTP Server - Host : smtp.gmail.com - Secure (SSL) - Port 465 
> * SMTP Server - Host : smtp.gmail.com - Secure (TLS) - Port 587 

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Outlook.com SMTP Ports & Settings **
> * SMTP Server - Host : smtp.live.com - Secure (TLS) - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Office365.com SMTP Ports & Settings **
> * SMTP Server - Host : smtp.office365.com - Secure (TLS) - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Yahoo Mail SMTP Ports & Settings **
> * SMTP Server - Host : smtp.mail.yahoo.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Yahoo Mail Plus SMTP Ports & Settings **
> * SMTP Server - Host : plus.smtp.mail.yahoo.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Yahoo UK SMTP Ports & Settings **
> * SMTP Server - Host : smtp.mail.yahoo.co.uk - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Yahoo Deutschland SMTP Ports & Settings **
> * SMTP Server - Host : smtp.mail.yahoo.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Yahoo Australia/New Zeland SMTP Ports & Settings **
> * SMTP Server - Host : smtp.mail.yahoo.com.au - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** O2 SMTP Ports & Settings **
> * SMTP Server - Host : smtp.o2.ie - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** O2.uk SMTP Ports & Settings **
> * SMTP Server - Host : smtp.o2.co.uk - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** AT&T SMTP Ports & Settings **
> * SMTP Server - Host : smtp.att.yahoo.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** NTL @ntlworld.com SMTP Ports & Settings **
> * SMTP Server - Host : smtp.ntlworld.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** BT Connect SMTP Ports & Settings **
> * SMTP Server - Host : pop3.btconnect.com - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** BT Openworld SMTP Ports & Settings **
> * SMTP Server - Host : mail.btopenworld.com - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** BT Internet SMTP Ports & Settings **
> * SMTP Server - Host : mail.btinternet.com - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Orange SMTP Ports & Settings **
> * SMTP Server - Host : smtp.orange.net - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Orange.uk SMTP Ports & Settings **
> * SMTP Server - Host : smtp.orange.co.uk - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Wanadoo UK SMTP Ports & Settings **
> * SMTP Server - Host : smtp.wanadoo.co.uk - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Hotmail SMTP Ports & Settings **
> * SMTP Server - Host : smtp.live.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** O2 Online Deutschland SMTP Ports & Settings **
> * SMTP Server - Host : mail.o2online.de - Non-Encrypted - Port 25

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** T-Online Deutschland SMTP Ports & Settings **
> * SMTP Server - Host : securesmtp.t-online.de -  Secure (TLS) - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** 1&1 (1and1) SMTP Ports & Settings **
> * SMTP Server - Host : smtp.1and1.com - Secure (TLS) - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** 1&1 Deutschland SMTP Ports & Settings **
> * SMTP Server - Host : smtp.1und1.de - Secure (TLS) - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Comcast SMTP Ports & Settings **
> * SMTP Server - Host : smtp.comcast.net - Non-Encrypted - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Verizon SMTP Ports & Settings **
> * SMTP Server - Host : outgoing.verizon.net - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Verizon (Yahoo hosted) SMTP Ports & Settings **
> * SMTP Server - Host : outgoing.yahoo.verizon.net - Non-Encrypted - Port 587

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** zoho Mail SMTP Ports & Settings **
> * SMTP Server - Host : smtp.zoho.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

> #### ** Mail.com SMTP Ports & Settings **
> * SMTP Server - Host : smtp.mail.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.


> #### ** GMX.com SMTP Ports & Settings **
> * SMTP Server - Host : smtp.gmx.com - Secure (SSL) - Port 465

Note :These SMTP Ports & Settings may be different depending upon your Host Provider. Please contact your Web Server Host for correct details.

== Installation ==

### Minimum requirements.  
*   Wordpress 2.7+  
*   PHP 5.x  
*   MySQL 5.x  

### Performing a new installation  

After downloading the ZIP file,  

1. Log in to the administrator panel.  
2. Go to Plugins Add > New > Upload.  
3. Click “Choose file” (“Browse”) and select the downloaded zip file.  

*For Mac Users*  
*Go to your Downloads folder and locate the folder with the plugin. Right-click on the folder and select Compress. Now you have a newly created .zip file which can be installed as described here.*  

1. Click “Install Now” button.  
2. Click “Activate Plugin” button for activating the plugin.  

If any problem occurs, please contact us at [support@tech-banker.com](mailto:support@tech-banker.com).


== Screenshots ==

1. Settings Page with Php Mailer as Transporder for sending Emails from your WordPress Site
2. Settings Page with SMTP as Transporder for sending Emails from your WordPress Site
3. Send Test Email Screen
4. Debugging Output Console Log
== Changelog ==

= 1.0 =

* Initial Release
