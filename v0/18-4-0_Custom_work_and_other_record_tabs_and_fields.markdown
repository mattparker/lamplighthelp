# 18.4.0    Custom {{work}} and other record tabs and fields

> It is possible to add additional tabs and fields to your {{work}}, {{outcome}} and other records through System Administration.

In the section 'Manage drop-down lists' you'll see options at the bottom to add for each type of record.

![System Admin - Add fields to records]({{imgpath}}1217a.png)

Each type of record works on the same principle, with the example below being for work records.  
The system is almost identical to adding Custom tabs and fields on profiles.  Please ensure you are familiar with this section first.  See:

__Adding fields to a work record__

Choose 'View, add and edit custom field on work records'.  You'll see three columns, with the first showing you a list of tabs available on your work records.  Depending on your set-up you may see one or more of the three standard tabs on the work record (When and where, Attendance, Details).  This is where you have custom fields added to these tabs.  You'll also see any custom tabs you have created.

Click on a tab on the left, and you'll see the fields for that tab in the centre column.  If you then click on a field, you'll see the field information, and options if applicable in the right column.  As shown below.

![System admin - Adding custom fields to records]({{imgpath}}1218a.png)

__Creating a new tab__

To create a new tab, select the button 'Click here to add' in the left-hand column.  You'll see a small pop-up box.  This will open a small pop-up box with the tab information.  In here you can name the tab, and select various options.  Some of these options are redundant in records, and apply only to profile fields.

* What type of person is this for:  No answer can be selected here, as records show all fields for all users.
* Restrict this field to managers/admins?:  Although you can tick this field, it does not function in this record.
* Projects: You can select which projects (If you have more than one project) this field should display for.
* You may also see fields about publishing, if you have the publishing module.  See section [24.0 Publishing Module](/help/index/v/{{version}}/p/24.0)
Click 'Save' to save the tab.

__Important__ You must always add a field to a tab, to ensure it remains editable and visible in System Administration.  If you do not, you'll have an empty tab in your record which you will be unable to edit.  In this case, please contact Lamplight for support.

![System Admin - tab information]({{imgpath}}1219a.png)

__Editing a tab__

To edit a tab, select the tab in the left-hand column, and when the tab information shows in the middle column, double click on the text 'Tab name', and edit the existing information (as above)

__Creating a field__

Select the required tab, and in the middle column, choose the button 'Click to add'. In the right-hand column, you'll see a new section appear 'Field: Click to add.'  Double click on the non-bold text 'Field: Click to add ‘and a pop--up box will open.  Again, some of the options show here are redundant for work records.

![System Admin - field information]({{imgpath}}1220a.png)

* Text: This is the name of the field.
* What type of person is this for:  No answer can be selected here, as records show all fields for all users.

* Type: This selects the type of field you will be creating.  By default, a new field will be a 'select' field, unless changed.  See information on types of fields below.

* Is this a required for: IF this is selected, a user will not be able to exit the tab without entering information.  Use very cautiously.
* Restrict this field to managers/admins?:  Although you can tick this field, it does not function in this record.
* Projects: You can select which projects (If you have more than one project) this field should display for.
* You may also see fields about publishing, if you have the publishing module.  See: 
Click save once you have completed the appropriate fields.

__Editing a field__

Choose the field you wish to edit in the centre column, and select it.  In the right-hand column, you will see the field information appear (you may need to scroll up if you have a long list of fields.)  Double click on the non-bold text, where it says 'Field: _name_.  From here follow the process as above to edit and save the field.

__Types of fields__

* Select box - Select a single option from the list of options.
* Multi-select box - to select several options, hold the ctrl key down and select the options you need.
* Plain text box - enter a short amount of free text.
* Plain text area - enter longer amounts of free text
* Rich text - enter free text here and add formatting as desired.
* Check box - click on the box to fill in a tick
* Radio button - click on the button to indicate a yes
* Dates - Dates are entered in UK format by selecting from the day/month/year select boxes or using the popup calendar.
* Date/Times - Dates and times are entered on a 24-hour clock from select boxes.
* Date of birth selector - Dates are entered in UK format by selecting from the day/month/year select boxes and a current age is displayed.  Date of birth fields also give you options in {{group}}s to do things like 'people aged between 18 and 24', and to look at anniversaries etc. So 'date of birth' fields can also be useful for things like 'Date of membership'.
* Number box - enter numbers only into a small text box.
* Caption - a label is added, to separate fields within a tab.
* Fixed text box - this is descriptive text that cannot be altered in profiles, but can be used to add informative text or reminders about the other information on the tab
* Year selector - choose the year from a drop-down (but not month or day)
* Radio buttons - select one: add several radio buttons, only one of which can be selected
* Checkboxes - select many: lets you select several options using tick boxes
* Charity number lookup - enter a Charity Commission registered number and Lamplight will add a link to their page on the Charity Commission website
* Twitter name: a text box that will let you look up their recent tweets
* Web address - for additional websites - and will provide a link to the site
 
__Adding fields to a system standard tab__

All records have the tabs 'Where and Where', 'Attendance', ( this may be called 'respondent' or 'Involved' in some cases), and Details.  You can add additional fields to these tabs, by 'creating' them in System Admin.  Create a field with the correct name as below, (Capitalisation is essential), and add fields to it.  You will be able to come back and edit/remove these fields, but will not see any of the standard fields.  These can only be changed by Lamplight.  Use the appropriate, correctly capitalised name as below.

![System Admin - adding fields to system tabs]({{imgpath}}1221a.png)

_{{Work}} records_
When and where
Attendance
Details

_{{Outcome}} records_
When and where
Respondent (If you have this tab)

_{{Referral}} records_
When and where
Attendance (If you have this tab)
Involving (If you have this tab)
details

_{{Grant}} records_
When and where
Attendance
details


__Adding custom columns to the 'Attendance' table__

The other option you'll see in the 'Manage drop-down lists' section is 'view and edit custom columns on the attendance table'.  If you look at the {{work}} records Attendance table in the attendance tab, you'll see that you have a number of columns, including name, attendance type, and role.  It's possible to add additional custom columns here, and you may already have some.

Follow the link, and you'll see a familiar three column set-up.  In this section, the first column is simply a label, as every field appears in the attendance table, and not in its own tab.  Follow the same procedure as for {{work}} records above, to create a new item in the left-hand column, calling it something useful for your team, as an aid to memory.

Click on the item in the left-hand column, and you'll be able to add a new field and options in the centre and then right columns.  Once created these will appear after the system tabs, in the {{work}} Record attendance table.

Things to consider
* The attendance table can become quickly crowded if you add many columns, and so consider what you need carefully, and the length of the field title.
* Reporting is more limited on custom fields than it is for normal fields in a work record.  You can report on them in {{work}} reports, and display them in a person's {{work}} records profile tab, but they can't be used in groups, and only in Dataviews using a custom template.
* You can hide other columns you don't need in the table, by right clicking in the table header row and deselecting ones you don't need.  Right click again and choose 'Save table columns layout' to always show only the selected rows.  This only applies to your user, and can be different for each person.


###### core module

