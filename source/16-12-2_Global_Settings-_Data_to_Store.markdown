# 16.12.2 Global Settings: Data to Store

> The 'Data to store' tab contains options relating to the types of records you want to create and what information you would like to include

See below for explanations of the different fields:

- **Do you want to use {{message}}s at all?**

   {Message}}s are an optional function in {{Lamplight}}. They are not used for reporting but can be a useful way of keeping track of things that need to be done.

   {{Message}}s are associated with a date and time, assigned a category and/or flag and can be marked as complete, along with a date and time, when accomplished. To add, edit and delete flag and category types, go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> {{Message}}s'.

   {{Message}}s are also linked to profiles and can be viewed directly in a profile’s ‘{{Message}}s’ tab, (you will only see this if the option is selected in your system).

   {Message}}s appear in a table, such as the one below. As this {{message}} has been associated with a database operator, it is showing up in the ‘{{Message}}s’ tab on their homepage.
 
   ![{{Message}}s Table](16.12.2a.png)

- **Do you want to allow bulk updating of the attendance table in {{work}} and other records?** 

   When adding profiles to the attendance table in a {{work}} record, {{referral}} record or {{outcome}} record, you must usually specify attendance type and role for each profile, as well as adding any notes.

   With this option enabled, there is an additional row in the table that allows you to edit these fields for all the visible rows of the attendance table at once.

   ![Bulk Update Attendance Table](16.12.2b.png)

- **Do you want to allow adding new service user profiles from {{work}}, {{referral}} etc. records, even if you have profile essential fields enabled (see previous tab)?**

   If you have specified essential fields that must be completed when adding profiles, it is not usually possible to create new profiles from within a {{work}}, {{referral}} or {{outcome}} record. This is because profiles created in this way will not have the essential fields completed was you add them.

   Enabling this option will mean that profiles can be created in the attendance table of {{activity}} records even though they will  not have all the essential information completed at that time.

   If you want to use this option, it is important to remember that you will need to go back to complete the essential information for these profiles once you have finished creating the {{activity}} record.
   

### {{Work}} Records

- **Do you want to store {{work}} records?**

   {{Work}} records are switched on by default in {{Lamplight}}. They allow you to record {{work}} they you have done / will be doing in future, and can be used in many ways including producing detailed {{report}}s. For most {{Lamplight}} users, they represent a key element of their system.

   If you do not use {{Lamplight}} to record your {{work}}, for example if you only use your system to track contact information, you can disable {{work}} records entirely using this option. This means that you will not see the option to add them or report on them in your system.

- **What is the default length of one {{work}} record (minutes)?**

   When entering {{work}} records in {{Lamplight}}, there is a default duration of sixty minutes. This means that when you enter the  start time for a {{work}} record, the end time is automatically set to sixty minutes later (you can always edit this to the actual end time as needed). 

   If you usually see clients for a set amount of time that it not sixty minutes, changing this setting will reduce the amount of data entry you need to do for each {{work}} record. For example, if a typical appointment within your organisation lasts thirty minutes, it makes sense to change this setting to thirty.

- **Do you want to use {{message}}s with {{work}} records?**  

   If you have enabled {{message}}s in your system, there will be a ‘{{message}}s’ tab on {{work}} records. This allows you to enter {{message}}s while still in the {{work}} record. These will still appear in the tables on the home page and in profile tabs as usual, but they will also be visible from within the work record.
   You can disable this option to hide the tab in {{work}} records if you prefer.

- **How many years back should the dates go in {{work}} records?** 

   When creating or editing a {{work}} record, you select the year using a drop-down menu. By default, this list goes back ten years, which is enough for most purposes. 
 
   If you need to enter historical records onto your system, you can adjust this setting so that the list goes back further, allowing you to enter older records.

- **Do you want to add an "add to diary" tickbox on {{work}} records?**  

   When a {{work}} record is created it is added to the diaries on the home page. This makes them visible in the ‘My Diary’ tab and the shared ‘Diary’ tab.

   This option allows you add a tickbox to the bottom of the 'When and where' tab on {{work}} records which allows you to choose whether each record should be added to these diaries.
 
   ![Add to Diary Tickbox](16.12.2c.png)
 
   Note that if you enable this, operators will be able to create {{work}} records that do not show on the home page diary, but these records remain accessible to all operators as normal (for example in {{work}} > view > {{work}}) so this feature does not restrict access to information.

- **Do you want plain text or rich text boxes for summary, description and follow up?**   

   When entering summary, description and follow-up information in {{work}} records, by default the text boxes are ‘rich text' boxes, which means that they offer options for formatting, including different typeface, different font sizes, bold, italic and underlined type, etc. as in the example below.

   ![Rich Text](16.12.2d.png)

   If you don’t require these formatting options, this option changes these to plain text boxes instead, as in the example below.

   ![Plain Text](16.12.2e.png)


### {{Outcome}} Records

- **Do you want to store {{outcome}} records?**  

   {{Outcome}}s in {{Lamplight}} are used to track change over time. An {{outcome}} record functions as a snapshot of one point in time, and multiple {{outcome}} records can be compared to measure difference. They are usually used to understand the difference an organisation’s work is making, and are very useful for capturing numerical numerical information for reports or funding proposals. By default, {{outcome}} records are enabled.

   This functionality can be disabled if {{outcome}}s are not needed in your system.
   
   For more on {{outcome}}s see [8.0.0 {{Outcome}}s](/help/index/p/8.0.0)

- **Do you want to use {{message}}s with {{outcome}} records?**   

   With this option, {{message}}s can be associated with {{outcome}} records in the same way that they can be associated with {{work}} records and {{referral}} records (see above). A '{{Message}}s' tab becomes available when adding a new {{outcome}} record through the main menu, as shown here:
 
   ![{{Message}}s on an {{Outcome}} Record](16.12.2f.png)

- **Do you want to use simple or tabular attendance information on {{outcome}} records?**   

   By default, profiles added as attendees on an {{outcome}} record are listed in a table. This allows for multiple {{people}} to be added in different roles, as in the example below.

   ![Normal Attendance Table](16.12.2g.png)

   If this functionality is not required, and the most that will be listed on an {{outcome}} record is one service user profile and one staff profile, the simple search box may be sufficient. It appears as in the example below. An important thing to remember when using this simple view is that you must select the profile from the search options that appear as you type, rather than just typing the name. This will ensure that it is linked to the correct profile.
 
   ![Tabluar Attendance Table](16.12.2h.png)

- **Tick the "our {{work}}" checkboxes by default**   

   These checkboxes are used to indicate whether a change in {{outcome}} results has been as a result of your work. They are ticked by default unless you deselect this option. You can't report on this information - it is just for information when looking at the specific record.

   ![Our Work Checkboxes](16.12.2i.png)


### {{Referral}} Records

- **Do you want to store {{referral}} details?**   

   {{Referral}} records are one of the core types of information that can be recorded in {{Lamplight}}. In their simplest form, they track who has been referred, who has referred them and who they have been referred to, along with {{referral}} reason, additional notes and details of the date, time and relevant {{work}} area. They can also be configured to record different ways in which one {{person}} is directed to another contact or service, for example signposting. If you do not require this type of information to be recorded in {{Lamplight}}, you can disable the functionality with this option.

- **Do you want to use {{message}}s with {{referral}} records?**   

   Just as you can associate {{message}}s with {{work}} records or {{outcome}} records, you can choose to associate them with {{referral}} records. This option is enabled by default but can be turned off if you don't need it.

- **Do you want to use simple or tabular attendance information on {{referral}} records?**   

   You can add profiles can be added to the attendance table in {{referral}} records using either the default table style or simple search boxes. While in the default table you can add as many attendees in as many different roles as you want, in the simple table view on {{referral}} records you are restricted to three attendees: referrer, service user referred and who they were referred to.

   ![Referral Record Simple Table](16.12.2j.png)
 
- **Show date to when adding {{referral}} records?**   

   You may only need to record the time and date of a {{referral}}, in which case you will not require this option. This allows you to record a duration as well, which will give you the fields to enter the time and date to, as shown below.

   ![Duration in {{Referral}} Records](16.12.2k.png)
 

### {{Grant}} Records

- **Do you want to store {{grant}} details?**   

   {{Lamplight}} can be used to record details of {{grant}}s. As well as time and date, {{workarea}} and attendance information (which are common across all types of record), {{grant}} records can contain information about whether a {{grant}} is for capital or revenue, with an approval date, {{grant}} amount, and text fields for summary, description and monitoring requirements. If you don’t use {{Lamplight}} for recording {{grant}} information, disabling this option will prevent menu items relating to it from appearing.

- **Do you want to use {{message}}s with {{grant}} records?**   

   As with {{work}} records, {{outcome}} records and {{referral}} records, you can choose whether to enable {{message}}s with grant records. Disabling this option will prevent the ‘{{Message}}s’ tab from appearing when entering grant records.


### {{Eval}} Records

- **Do you want to use {{message}}s with {{eval}} records?**  

   As with {{work}} records, {{outcome}} records, {{referral}} records and grant records, you can choose whether to enable {{message}}s with {{eval}} records. Disabling this option will prevent the ‘{{Message}}s’ tab from appearing when entering {{eval}} records.

- **Do you want to use simple or tabular attendance information on {{eval}} records?**   

   As with respondents in {{outcome}} and {{referral}} records, profiles can be added to the {{eval}} records attendance table using either the default table style or simple search boxes. In the simple search box view on {{eval}} records, there is just one field for ‘Who completed the {{eval}}’, as shown below.

   ![Simple Table on {{Eval}}s](16.12.2l.png)

- **Show date to when adding {{eval}} records?**   

   As with {{referral}} records, you can choose to specify a ‘date to’ as well as a ‘date from’ for {{eval}} records, allowing them to last for a specific duration rather than being recorded as a single point in time.


###### core system
