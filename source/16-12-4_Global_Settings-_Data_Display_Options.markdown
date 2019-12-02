# 16.12.4 <i class="fas fa-tools"></i> Global Settings: Data Display Options

> System administrators can change what is seen by default in {{Lamplight}} tables



The fields in this tab are:

### Data Tables: {{Work}} and Similar Records

#### Do you want data tables to display full details?

   This option changes the default table layout in tables where profiles are listed (for example in {{people}}>view>{{user}}>all) to include ‘First name’, ‘Surname’ and ‘Alternative name’.
 
    ![Table with Full Details](16.12.4a.png)
    
   If this option is not selected, only the ‘Name’ field will be displayed by default.
        
    ![Table with Name Only](16.12.4b.png)
 
   It will remain possible to change columns displayed in these tables individually using the contextual menu shown when right-clicking on the table header.
   
   ![Contextual Menu on Table of {{People}}](16.12.4c.png)
   
 
#### Do you want data tables to display case details?

   If you select this option, your {{activity}}>view tables (e.g. {{work}}, {{outcome}}s etc.) will automatically display case information when they open. The fields include case ID, case name and case open. If this box is left unticked it is still possible to choose to view these columns by right clicking on the table header row and ticking the options that you wish to include.

#### Do you want {{work}} data tables to add hidden columns for description and follow up text?

  Choosing this option will add ‘description’ and ‘follow-up’ options to the header of the {{activity}} > view > {{work}} table, so that you can view any information added to those work record fields. It will also add a ‘{{referral}} description’ option to the {{activity}} > view > {{referral}}s table, which displays information from the direction, success and notes fields of {{referral}} records.
  
  ![Hidden Columns in Context Menu](16.12.4d.png)
 
#### Do you want data tables to display locations?

  This option governs whether there is a ‘Location’ column in the tables accessible through {{activity}} > view in the main menu. Enabling these can be useful as it allows the entries to be sorted by location (by clicking on the column header).
  
  ![Table Showing Location](16.12.4e.png)
 
#### Do you want search bars within profile tabs (for {{work}}, {{referral}}, {{grant}}, {{comm}} and {{eval}} tabs)?

   This option enables the search bar in each of the listed profile tabs. Clicking the 'filter' button on the search bar will expand it to show options that can be used to filter the results displayed in the table below. It will also allow you to add certain extra data columns. This option can be useful if you have many records linked to profiles and need to filter them to get a useful view of the data.
   
   ![Search Bar on Profile {{Work}} Records](16.12.4f.png)
 
   Note that having the search bar available can confuse database operators using the system for the first time, as tables will only show records within a date range (this is set by default to show two months in the past and two months in the future), which can lead to people thinking their old data has disappeared. When this option is disabled, all records are shown.  When you have a lot of data (hundreds of records), this will mean that the tab will be slower to load.


### Data Tables: {{People}}

#### How do you want lists of {{people}} sorted by default?

   This option changes how lists of {{people}} are sorted in tables such as the ones accessible via {{people}} -> view in the main menu. Irrespective of this setting, it remains possible to change the way profiles are sorted by clicking on the column headers. This option simply changes the way they are presented before you click anything, potentially saving time if you always want profiles listed in a certain order.
   
#### Do you want to sort names by full name or surname, firstname?

   It is advised that you make your selection of how you want lists sorted from the field above, and then you will not need to use this one.

#### In what order do you want lists of {{people}} sorted by default?

   This setting determines whether results are sorted in ascending order (i.e. from lowest to highest value, or from A to Z) or descending order (i.e. from highest to lowest value, or from Z to A). It is used in conjunction with the setting How do you want lists of {{people}} sorted by default? to decide how results are displayed in tables. You can reverse this order whenever viewing a table by clicking on the table column header. Clicking again will reverse the order.
   
### Data Display: Miscellaneous

#### How many rows per page do you want your tables to display?

   This determines how many items appear on each page when tables are displayed. If there are more records that can be shown on one page, the options above the table (as shown below) allow you to navigate to other pages of results.
   
   ![Table Navigation Tools](16.12.4g.png)
 
   Choosing a lower value can speed up loading times and might be preferable if you are using an older computer or a mobile data connection. Higher values will mean more results are displayed on each page, giving you access to more results in one place.
As you can see in the image above, once you’ve run the table you still have the option to display different numbers of results on each page. This setting simply governs the default behaviour.

#### Should custom field tables display date the data was added?

   It is possible to turn groups of custom fields into tables. This can be useful if you want to add sets of data on numerous occasions. This is achieved in the custom tabs and fields editor by clicking and dragging a box around a series of fields, as shown here.
   
   ![Creating Linked Fields](16.12.4h.png)
  
   Once grouped, fields are displayed with a green box around them to show that they have been made into a table. This can be undone by simply dragging another box around the same items.
   
   These fields will then be displayed as a table, as shown here.
   
   ![Linked Fields in the Profile](16.12.4i.png)
 
   Enabling the global setting for custom field tables to display date the data was added will add an extra column to the table to record the date of the entry, as shown here.
   
   ![Linked Fields with Date](16.12.4j.png)
 
#### Do you want to enable multi-{{project}} {{group}} reports?
  
   If you have more than one {{Lamplight}} {{project}}, this option enables you to run multi-{{project}} {{group}} reports. They can be accessed through {{group}}s -> view -> multi {{project}} report, as shown here.
   
   ![Multi-{{project}} Reports](16.12.4k.png)
 
   This allows database operators who have access to more than one {{project}} to use a {{group}} data view to present information across multiple projects. This is only applicable to auto-{{group}}s, as manual {{group}}s cannot be shared across projects.

### Translating Terms within {{Lamplight}}

#### Do you want translations of terms within your system to be {{project}} specific?

   If you have multiple {{Lamplight}} systems, selecting this option allows you to use different languages for each one. For example, one could be in English, and another in French.
   
#### What languages do you want to use?

   Use this box to specify the languages that you want to use in your system. The default is British English (en_GB), but you can add others to the list, each separated with a semi colon (;). You can look up a list of 'language codes' on the internet if you do not know the abbreviation for one that you need.



###### core system
