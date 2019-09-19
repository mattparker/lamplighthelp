# 16.13.1 Preparing Profile Information to Import to {{Lamplight}}

> You will need to have your information in an Excel csv spreadsheet, formatted so that it wil be imported to the correct fields



### Preparing Information

Information is imported by uploading a spreadsheet in .csv format. It can be imported into standard and custom profile fields, but not repeating fields. 

- The spreadsheet should look like the example below, with field names across the top, and content below in each column. 
- The name of each column header must exactly match the field name in your Lamplight system (you may want to copy and paste the text from Lamplight to be certain). Lamplight will not be able to import data that it does not recognise, and it uses column headers to work out where the information should go. 

![Preparing the Spreadsheet](16.13.1a.png)

- There is no need to enter tab information, just the field name. 
- Only one combination of profile type ({{person}}, {{org}} or {{family}}) and role ({{user}}, {{staff}}, {{volunteer}}, {{contact}} or {{funder}}) can be imported at a time, so a separate sheet is needed for each (e.g. one for {{person}}>{{user}}s, another for {{person}}>{{staff}}).
- The spreadsheet should have a column for each field to be imported, and must be saved in .csv format. Note that saving an Excel workbook in .csv format will only save the current tab as .csv files do not support multiple sheets.


#### Field Names

The built-in headers that Lamplight will recognise for profile fields are:
- id.
- name (for {{org}}s only, not {{people}}).
- alternative_name.
- title (text values must match values in the title list).
- suffix (text values must match values in the suffix list).
- first_name.
- surname.
- current_address_line_1 (and the same format for lines 2-5).
- postcode.
- phone.
- mobile.
- email.
- web.
- allow_email (a value of 0 for no, or 1 for yes).
- allow_post (a value of 0 for no, or 1 for yes).

With the publishing module:

- publish (a value of 0 for no, or 1 for yes).
- publish_summary.
- publish_update.


Columns can be in any order, and need not be included if they won’t contain any data. Additional columns for custom fields can be added to this list. 

#### Formatting Tips  

- Fields are case sensitive. Copy them character-for-character, space-for-space, with the same capitalisation (although the system will attempt to guess in cases where there is not an exact match).
- You can download all the field names and other settings in the System Administration menu to help with this (under 'File Transfer -> Download filed settings for your sytsem).
- For multi-select fields, separate values with semi-colons (;) but no spaces (e.g. yes;no;not applicable). Values in drop-down type fields must match the options in the system exactly. If the options are ‘male’ and ‘female’ but the .csv contains ‘m’ and ‘f’, the data will not be imported.
- Checkboxes can be defined as ‘Yes’, or left blank for no.
- For multi-select radio buttons and checkboxes, simply enter the values.
- Dates should be entered in yyyy-mm-dd format. Excel stores dates as numbers (and displays them as dates), but in the .csv file they must be text strings. You can use the Excel function TEXT for this: =TEXT(A2, "yyyy-mm-dd")will format the date in cell A2 as a string.
- Number fields should be converted to ‘text only’ in Excel (Cells, format, number), or they will lose the 0 at the start of the number.
- Once you’ve saved your .csv, you may want to re-open it, and check everything looks as it should. 


### Preparing Information to Upload to Existing Profiles

Information can be uploaded to existing profiles. This tends to be more complex than creating new profiles, and it is therefore not recommended as a regular process.

Lamplight can match uploaded data to existing profiles using the ID field (a unique reference number for each profile in Lamplight). The simplest way to find profile IDs is to use a {{group}} with a {{group}} data view, although you can also find the ID number manually.

#### Downloading Names and Profile IDs 
Create a {{group}} data view showing the profile ID field. Create a {{group}} of the profiles into which data will be imported, and then view it using the {{group}} data view. Ensure that ‘Show All’ records is selected at the top of the table, then click the ‘Download’ link at the bottom and open the file in Excel.

![Downloading the {{Group}} with a Data View](16.13.1b.png) 
 
This spreadsheet displays the name and profile ID for each profile, making it easier to match the information to be imported to the appropriate profile ID.

#### Adding Profile IDs Manually
Profile IDs can also be added to the spreadsheet manually. They can be found either using the method above or by opening the profile and moving the cursor over the name at the top.


### Completing

Once the spreadsheet is formatted correctly, with the correct profile IDs, you can delete the names (unless they are a field that you are importing) as the profile IDs serve as the key identifier. 


###### core module