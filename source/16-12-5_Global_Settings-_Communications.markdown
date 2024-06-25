# 16.12.5 <i class="fas fa-tools"></i> Global Settings: {{Comm}}s

> In the section the System Administrator can specify the reply address for SMS (if you have it) and email, allow {{Lamplight}} to store international mobile phone numbers in the contact details tab, enable postcode checking and decide some default communications settings. If you have the {{comm}}s module, you can also set up a link to Mailchimp here



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
 
#### Which email server do you want to use?

Here you decide if emails sent using {{Lamplight}} are to come from a central email address, or through individual staff email accounts.  If you have the Email Module, you need to select, 'Send through Lamplight Servers'.

#### How many recipients per email?
If you are sending emails to a large number of recipients, these emails can be sent in batches to make the process faster. Many email providers place a limit on the number per batch, so you should enter the amount as recommended by your email provider. If you do not apply a limit, it is likely the emails will fail to send. Set the maximum number of recipients here. If you set it to 0 then emails will not be batched at all.

#### Default reply-to email address

   If this field is left blank, replies to emails sent using {{Lamplight}} will be received in the email address of the person sending the communication, i.e. the address they use to log into {{Lamplight}}.  If your usual process is for all replies to be addressed to a central email inbox, you need to specify it here.
      
#### Staff member to receive unsubscribe notifications

   When emails are sent through {{Lamplight}} an unsubscribe link is appended to all messages. If this is clicked, the staff member specified will receive a {{message}} notifying them that the profile has asked to be removed from the mailing list.
   
#### Allow cc emails to be sent from {{Lamplight}}?

  By default, cc emails are not allowed to help avoid accidental data breaches (cc email is one of the most common ways for this to happen).  If you really do need this functionality you can enable it here.

### Postcode checks

#### Do you want to check postcodes?
Tick this option if you want the postcodes you enter to adhere to a specific format.

#### Which postcode formats do you wish to allow?
The options you select here will depend on the countries you enter profile addresses for.  If you need an alternative format that is not listed, please let us know.

### Mobile Phone and SMS {{Comm}}s Settings
   
#### Default reply-to mobile number (for SMS)

   This option allows a telephone number to be specified for replies from SMS messages sent through {{Lamplight}}.  This is a required field.  If you do not wish to receive replies from text messages you send, please enter 'No reply' in the field.

#### What format mobile numbers to allow?

Different country's use different formatting for their mobile phone numbers, and it is not possible to save invalid numbers in	{{lamplight}}.  Please select the formats relevant to your organisation.  

#### Enable SMS sending?
Tick this box if you want to use {{lamplight}} to send text messages.  For more information see:  https://lamplight.online/en/help/index/v/2/p/21.4/q/sms
   
#### 24x account username and password for sending SMS messages

   Once you have created an account with 24x, add your username and password here to connect your account to {{lamplight}}.  You will also need this information when you come to top up SMS credits, so you can continue to send messages from your {{Lamplight}} system. 24x is the company that sends the actual text messages. This means you access your account directly to top up with credits and view reports. You can log in to the 24x control panel at [http://24x.com/](http://24x.com).
   
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
