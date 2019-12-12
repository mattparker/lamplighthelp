# 16.7.5  <i class="fa fa-cogs"></i> Adding Custom Columns to the Attendance Table

> You can add custom columns to the attendance table you see in {{work}} records



The other option you'll see in '{{Work}} Record Custom Tabs and Fields' is 'Manage custom columns on the attendance table'.  

If you look at the 'Attendance' tab in a {{Work}} record you will see the attendance table. There are a number of columns, including name, attendance type, and role.  It's possible to add additional custom columns here (you may already have some.) However, the attendance table can become quickly crowded if you add too many columns, and so consider what you need carefully.

### Finding your Custom Columns
- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> {{Work}} Records Custom Tabs and Fields -> Manage custom columns on the attendance table'.

If you have any existing custom columns in your system you will see a list of them here. 

### Adding Sets

If you want to add new columns, first you will need at least one set. Column sets are for adminstrative convenience in system admin - they are sometimes used to group columns together. You will not see them in the table itself, but they could be used for reference in future. You can put any number of columns in one set.

#### To Add a Single Set

- Click on the 'add new set' button. In the pop-up box you'll need to enter:
   - Set name -  this will be what you see at the top of the attendance table column.
   - If you have more than one {{project}}, which ones you would like it to be included in. 
- Once you have finished here click 'Update'. Remember, your changes will not be finally saved until you click on the 'save all changes' button at the top or bottom of the custom fields page. 

#### To Bulk Add Sets

- Click on 'bulk add set', then add any set names to the text box that opens up. These should be separated by a semi-colon (;) - you do not need a space before each new one. For example, 'Set 1;Set 2;Set 3'.
- When you have finished, click 'Update'. Remember, your changes will not be finally saved until you click on the 'save all changes' button at the top or bottom of the custom fields page. 
- If you want to share your custom columns across different {{Lamplight}} {{project}}s, you will need to go back to each set in the list and choose the {{project}}s you would like them to be visible to.


### Adding Columns

- Click on the set that you would like to add columns to. If there are already columns in this set you will see them listed here. If it is  a new set you will see the option to click to add a new column. 

#### Adding a Single Column

- Either click the 'add new column' button which is above the list of existing ones, or, if it is a new set, click the 'add new field to get started' button in the tab itself.  This opens a pop-up box. Complete the details with:

   ![Add a Field to a Tab](16.7.2e.png)

   ![Adding a new field](16.7.2f.png)

- The 'Field name' (this is the text you will see at the top of the attendance table column, so keep it short).
- Whether it is a required field (if you choose this option it will not be possible to edit the table and save it without putting data in this field).
- Type: This selects the type of field you will be creating. By default, a new field will be a 'select' field, unless changed. (For types of custom field see [16.7.3 Types of Custom Tab and Field in {{Activity}} Records](/help/index/p/16.7.3). Reporting is more limited on custom attendance table fields than for normal fields in a {{work}} record.  You can use them to present your {{report}} (as either row or column data) in {{work}} {{report}}s, and display them in a person's {{work}} records profile tab, but they can't be used in {{group}}s, and only in data views when using a custom template. 
   In addition:
   - Captions and fixed text fields do not work with attendance table columns (even though it is still possible to select them.) If you create these then the attendance table will not display correctly.
   - Look-up fields will function only as text boxes.
   - Radio fields will not show any options.
- {{Project}}s: if you have more than one {{project}} in your system, you can select ones the field will be displayed in. 
- If you have the Publishing Module you will also see fields about publishing. See [28.3.0 Publishing Module: Publishing Records to the Remote Site](/help/index/p/28.3.0). 
- When you have finished, click 'Update'. Remember, you will also need to click 'save all changes' before leaving the main custom fields page, or you will lose your new column. 
- The column that you have just added will now appear in the set.
  
 ![New Field in Tab](16.7.2g.png) 
 
#### Bulk Adding Columns

- Click on 'bulk add option' beneath the header of the set you would like to include them in. This opens a pop-up box.
- Type the names of all the columns that you are adding in the text box (again, remember that this is what will appear in the attendance table header bar, so keep the names short) each one separated by a semi-colon (;). You do not need a space before new ones. For example, 'Paid subs?;Behaviour rating;Weekly contribution'.
- When you have finished, click 'add all'. Don't forget, these are not finally saved until you click on the 'save all changes' at the top or bottom of the custom fields page before exiting - you still need to choose the type of field it is, and whether it is shared with other {{project}}s, for example. 
- You will now see all your new columns at the bottom of the list. 
- Click on each one in turn and choose the pen and paper icon to open it for editing. Their names will already be entered into the form, but you will need to add the other details for them, such as type of field, as described for a single tab above.
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) You're now ready to add options to your fields, as necessary. 

### Setting Options
   
The column type that you have just added may need some options (for example, if you've added checkboxes, you might want the options 'Yes' and 'No'.) Click on its name to open it, then if you can't see the buttons which allow you to add options, click on the three dots to the right of the column name. 

#### Add a Single Option

- To add your options one at a time, click on the 'add new option' button. This opens a pop-up box where you add the text of your option (in the previous example this would be 'Yes'). 
- Click 'Update' when you have finished. 
- Continue adding all the options you need in this way.

#### Add a Number of Options at Once

- If you have a column based on a field with a number of different options, click on 'bulk add option'. 
- Type all your options in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. For example, 'Yes;No;Not known.'
- When you have finished, click 'add all'. They will appear in a list below the column name.

#### Add from a Built-in List

- Lamplight contains a number of built-in sets of options. To see what is there, click on the 'add from built-in list' button. They include yes/no; some demographic lists such as ethnicity, gender, religion and language; number lists; days and months. If you would like to use any of these lists as options for your column, click on the circle next to the appropriate one then click 'add'. 
- If you do not see any sets of options which are relevant to your column, click cancel to come out of the bulk lists again. 
- Once you have added options to your columns, do not forget to save them before leaving the page using the 'save all changes' tab which can be found at the top and bottom of the main Attendance Custom Fields page. 



##### Tags
System admin
Activity

###### core module
