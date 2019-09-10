# 16.12.6 Global Settings: Security Settings

> This is where System Administrators can set the amount of time before an automatic lockout happens, and restrict operators below manager level so that they can only view profiles and records of the people that they work with. It also contains the option to enable speech recognition

### Logout Time

- **Length of time in seconds before automatic logout happens**

You can set the length of time operators can leave their system open without it detecting any activity before they are automatically logged out and need to sign in again. This is a security feature aimed at stopping systems with sensitive data being left open at an unattended computer. Be aware that {{Lamplight}} cannot detect some activity, such as entering text. 

### 'My User' Set-up

The next three fields, restricting database operators, relate to a my user restriction. 

The ‘My User’ restriction allows for a stricter level of access limitation to Lamplight. Database operators can be linked to other profiles (such as clients on their caseload) using the ‘My User’ relationship. With the ‘My User’ restriction enabled, database operators with access levels of staff, data entry or reception will only be able to see information about those profiles to which this relationship has been specifically created.

- **Restrict operators below manager level to only view "my users" they are linked to.**

   As explained above, this will restrict anyone with a staff, data entry or reception level of access to the system so that they can only see the profiles of, and search for, people and organisations they are linke to by a 'my user' relationship.
   
- **Restrict operators below manager level to only view {{activity}} and {{linked case}} records linked to the "my users" they are linked to.**
   
   Similar to the above restriction, this restricts access to all {{work}} and other {{activity}} records so that those with the lower level of access will onloy be able to see records relating to people who are linked to them with a 'my user' relationship. This relates to the main menu options under 'activity -> view'.
   
- **If using "my users" restriction above, should newly added profiles be made a "my user".**

   By choosing this option, when a database user creates a new profile in the system, it will automatically be linked to them as 'my user'. This is to prevent the need for another operator with a higher level of access to go in and create the relationship before they can edit information in the profile.
   
### Speech Recognition

- **Allow operators to use speech recognition with {{Lamplight}}?**

   If you use Chrome it has built-in dictation which you can use to write your {{work}} records or other text. If you choose to enable speech recognition here, each operator will have the choice whether or not they would like to use it.

   You may have privacy concerns about this: Google will receive the audio of what you say in order to turn it into text. You can check their privacy policy at [https://www.google.com/chrome/privacy/whitepaper.html#speech](https://www.google.com/chrome/privacy/whitepaper.html#speech). If you do enable this option, when you click on a text box you’ll get a request to access your microphone: if you say yes, you’ll be able to dictate, and after each pause the text will appear in the box. You only need to allow access once on a particular browser, and you can revoke it at any time.



###### core module
