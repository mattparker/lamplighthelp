# 21.4.0 The {{Comm}}s Module: Using SMS in {{Lamplight}}

> With the {{Comm}}s Module you also have the option to send SMS through the system, and receive replies to a number you choose

#### Getting Started with SMS in {{Lamplight}}

If you have the {{Comm}}s Module and would like to start SMS direct from {{Lamplight}}, your system administrator will need to update the settings.

For more on this see 'Mobile Phone and SMS Communications Settings' in [16.12.5 Global Settings: Communications](/help/index/p/16.12.5). You'll also see a link to 24x here, which you can follow to but credits for your account. Once you're at their login page, you will see a link to create a new account.

#### Sending SMS Messages

To send an SMS from {{Lamplight}}:

   - Go to '{{activity}} -> {{comm}} -> create' in the main menu. Alternatively, if you're in the profile of a person you'd like to send the message to, click on their '{{comm}}' tab.
   - On this first '{{Comm}} type tab, fill in the time and {{workarea}} at the top if they are there (you may have chosen not to show these in global settings).
   - Choose 'SMS text message' from the 'Type' list. You will also see here how many text credits you have left in your account. 
   - Below this, choose **either** the number that return messages should be sent to, **or** an email address which replies will be forwarded to. If you choose the email address, you will be debited a text credit for each 160-character reply. If you want to send a text with no reply, you can fill in the 'Default reply-to mobile number' with a message of up to 10 characters, for example 'No reply', or some part of your organisation name.
   - You can also choose to send the message either 'now', which means it will go as soon as you press the 'send' button, or 'at the time and date specified above'. If you select this option, change the 'time from' dropdown at the top of the page to the time you would like the SMS to go out. Once you have added the message and pressed 'send', {{Lamplight}} will wait until the time you've given before releasing the message. 
   - Fill in the summary box so that you know the detail when this record is stored in your {{comm}}s table (e.g. invite sent to all Thursday attendees).
   - If you have more than one {{project}}, you will also see the option to share this record with other {{project}}s here.
   
![Adding and SMS in {{Comm}}s](21.4.0c.png)

   - The next tabs you will fill in as with other {{comm}}s:
      - Find your recipients (the message will only send to those who have a mobile number recorded in their profile and who allow contact by mobile phone)
      - Add your message details. You will see a count of the characters used under the text box. If you have selected to 'cut off the message at 160 characters' in global settings, {{Lamplight}} will only allow you to add 160 characters to the message. Also, if you are using merge fields and have someone with a long first name, for example, they could lose the end of your text.
      - Once you're happy with the message, press 'create/send'. This will send it to all recipients and save a copy in each of their profiles. 
      - If you want to save this as a draft without sending, choose 'save but do not send', then you can find it in the {{comm}}s table at a later time to edit. For more on viewing and editing {{comm}}s, see [21.5.0 {{Comm}}s Module: The {{Comm}}s Tab](/hep/index/21.5.0).


###### comms module
