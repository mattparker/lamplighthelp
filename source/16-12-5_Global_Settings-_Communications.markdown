# 16.12.5 <i class="fas fa-tools"></i> Global Settings: {{Comm}}s

> In the section the System Administrator can specify the reply address for SMS (if you have it) and email, allow {{Lamplight}} to store international mobile phone numbers in the contact details tab, and decide some default communications settings. If you have the {{comm}}s module, you can also set up a link to Mailchimp here



The fields in the {{comm}}s tab are:

### General {{Comm}}s Settings

#### Include your signature automatically at the bottom of new {{comm}}s?

  If this option is enabled, the database operator’s name will automatically be added to the message content when creating new {{comm}}s, saving them from typing it at the end of each {{comm}}.
  
#### Show date and {{workarea}} on {{comm}}s?

   This option governs whether date and {{workarea}} are to be specified for each {{comm}}. These appear in the ‘New {{comm}}’ page as shown here.
   
   ![Show Date and {{Workarea}} on {{Comm}}s](16.12.5a.png)
 
   These options provide criteria for filtering information when reporting on {{comm}}s. If this functionality is not required, the options for new {{comm}}s can be simplified by disabling this option.

#### Add me to blank or individual {{comm}}s?

   This option governs whether the profile of the database operator creating a {{comm}} will be added as a recipient to {{comm}}s created using {{work}} -> {{comm}} in the main menu or from the contextual menu of a record, such as a {{work}} record, as shown below.
   
   ![Adding DB Operator to a {{Comm}} Automatically](16.12.5b.png)
 
   The database operator will not be added to a {{comm}} created using the right-click contextual menu from a {{group}} (unless their profile is among those in the {{group}}), as shown in this image.
   
   ![Creating a {{Comm}} from a {{Group}}](16.12.5c.png)
 
   If the option is disabled, the database operator’s profile will not be added automatically to any new {{comm}}s.
   
#### Add a {{message}} tab to {{comm}}s?

   This option adds a ‘{{Message}}’ tab to {{comm}}s so tasks can be associated with {{comm}}s as they might be other types of record. It appears as shown below.
   
   ![Adding a {{Message}} Tab to {{Comm}}s](16.12.5d.png)
 
 
### Email {{Comm}}s Settings
 
#### Default reply-to email address

   Unless an email address is specified here, replies to emails sent using {{Lamplight}} will be sent to the email address of the person sending the communication, i.e. the address they use to log into {{Lamplight}}. An email address entered in this box will be used instead, and this will apply to all users. If you want all replies to be addressed to a central email inbox, specify it here.
   
#### Staff member to receive unsubscribe notifications

   When emails are sent through {{Lamplight}} an unsubscribe link is appended to all messages. If this is clicked, the staff member specified will receive a task notifying them that the profile has asked to be removed from the mailing list.
   
#### Allow cc emails to be sent from {{Lamplight}}?

  By default cc emails are not allowed, to help avoid accidental data breaches (cc email is one of the most common ways for this to happen).  If you really do need this functionality you can enable it here.


### Postcode checks

   This controls the checks on postcodes (zip codes) when entering data. You can choose which territory formats you wish to allow in your system. 

Please contact us if you require other territories not included on this list.

### Mobile Phone and SMS {{Comm}}s Settings
   
#### Default reply-to mobile number (for SMS)

   This option allows a telephone number to be specified for replies to SMS messages sent through {{Lamplight}}.

#### What format mobile numbers to allow?

   By default, mobile phone numbers are expected to be UK mobile numbers, and it is not possible to save invalid numbers.  You can allow other formats of mobile numbers from other territories if required.
Note that if you use 24x sms messaging through {{Lamplight}}, you may be charged additional fees for sending to non-UK numbers.

Please contact us if you require other territories not included on this list.

#### 24x account username and password for sending SMS messages

   You will need these when you come to top up SMS credits so that you can continue to send from your {{Lamplight}} 
   system. 24x is the company that sends the actual text messages. This means you can access your account directly 
   to top up with credits and view reports. You can log in to the 24x control panel at [https://24x.com/](https://24x.com).
   
#### Current credits available

   This will show you how many credits you have remaining on your account. There is also a link to 24x.com here.
   
#### Always cut messages short to 160 characters
   
   This option allows you to make sure that text messages sent can only use 1 credit each. With mail merge options, someone with a long name may mean the text message you thought would be less than 160 characters ends up going over and costing you double. Ticking this option will automatically cut off the message at 160 characters.
   
#### Allow SMS to reply to an email address

   Ticking this option means that any replies to an SMS are forwarded to the email address you specify. Please note that each reply costs an extra 24x credit, and recipients will see a different ‘from’ number. If you enable this, when you come to send an SMS you have the option of providing an email address. If you do not do this the mobile number you provide will be the reply-to number.
   

### Mailing Label {{Comm}}s Settings

#### Default mailing label size

   When creating mailing labels, there is a tab that allows you to specify the type of label, from a list of standard Avery sizes.
 
   If you know that database operators will usually use the same size label, it can simplify the process to set a default size using this option.
   
#### Default address block/text to use when creating mailing labels

   This field allows you to specify the text that is automatically added when creating mailing labels. This is usually address merge fields. If this field is left blank, the default content is as shown below.
   
   ![Text Block Default Address for Mailing Labels](16.12.5e.png)
   
   
### Mailchimp Settings

Mailchimp can be used to send bulk email (e.g. newsletters) to your users.  You can set up {{Lamplight}} to send email addresses to Mailchimp in order to send email to them.  This is generally a better option than trying to send through your own email.  You will need the {{comm}}s module, and you'll need to sign up for Mailchimp (they have very good deals for charities).  If you don't see the Mailchimp options in the {{Lamplight}} configuration screen you'll need to contact us to enable it.

Setting up Mailchimp is covered in [21.2.2 Setting up Mailchimp in {{Lamplight}}](/help/index/p/21.2.2).
   

    
###### core module
