# 16.7.5  <i class="fa fa-cogs"></i> Adding Custom Columns to the Attendance Table

> You can add custom columns to the attendance table you see in {{work}} records



The other option you'll see in '{{Work}} Record Custom Tabs and Fields' is 'Manage custom columns on the attendance table'.  

If you look at the 'Attendance' tab in a {{work}} record you will see the attendance table. There are a number of columns, including name, attendance type, and role.  It's possible to add additional custom columns here (you may already have some.) However, the attendance table can become quickly crowded if you add too many columns, so consider what you need carefully.

### Finding your Custom Columns

- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> {{Work}} Records Custom Tabs and Fields -> Manage custom columns on the attendance table'.

If you have any existing custom columns in your system you will see a list of them here. 

### Adding Sets

If you want to add new columns, first you will need at least one set. Column sets are for adminstrative convenience in system admin - they are sometimes used to group columns together. You will not see them in the table itself, and you can put any number of columns in one set.

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

- Click on the set that you would like to add columns to. If there are already columns in this set you will see them listed here. If it is  an empty set you will see the option to click to add a new column. 

#### Adding a Single Column

- Either click the 'add new column' button which is above the list of existing ones, or, if it is a new set, click the 'add new field to get started' button in the tab itself.  This opens a pop-up box. Complete the details with:

   ![Add a Field to a Tab](16.7.2e.png)

   ![Adding a new field](16.7.2f.png)

- The 'Field name' (this is the text you will see at the top of the attendance table column, so keep it short).
- Whether it is a required field (if you choose this option, when you are in the {{work}} record it will not be possible to edit the table and save it without putting data in this field).
- Type: This selects the type of field you will be creating. By default, a new field will be a 'select' field, unless changed. (For types of custom field see [16.7.3 Types of Custom Tab and Field in {{Activity}} Records](/help/index/p/16.7.3). Reporting is more limited on custom attendance table fields than for normal fields in a {{work}} record.  You can use them to present your {{report}} (as either row or column data) in {{work}} {{report}}s, and display them in a person's {{work}} records profile tab, but they can't be used in {{group}}s, and you will need a custom template to use them in data views. 
   In addition:
   - Captions and fixed text fields do not work with attendance table columns (even though it is still possible to select them.) If you create these then the attendance table will not display correctly.
   - Look-up fields (such as charity number) will function only as text boxes.
   - Radio button fields will not show any options.
- {{Project}}s: if you have more than one {{project}} in your system, you can select the ones the column will be displayed in. 
- When you have finished, click 'Update'. 
- The column that you have just added will now appear in the set. Remember, you will also need to click 'save all changes' before leaving the main custom fields page, or you will lose your new column. 
  
 ![New Field in Tab](16.7.2g.png) 
 
#### Bulk Adding Columns

- Click on 'bulk add option' beneath the header of the set you would like to include them in. This opens a pop-up box.
- Type the names of all the columns that you are adding in the text box (again, remember that this is what will appear in the attendance table header bar, so keep the names short) each one separated by a semi-colon (;). You do not need a space before new ones. For example, 'Paid subs?;Behaviour rating;Weekly contribution'.
- When you have finished, click 'add all'. 
- You will now see all your new columns at the bottom of the list, and you need to add the details to them.
- Click on each one in turn and choose the pen and paper icon to open it for editing. The name will already be entered into the form, but you will need to add the other details for them, such as type of field, as described for a single tab above.
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) You're now ready to add options to your fields, as necessary. 

### Setting Options
   
The column type that you have just added may need some options (for example, if you've added checkboxes, you might want the options 'Yes' and 'No'.) Click on the column name to open it, and there will be buttons allowing you to add options at the bottom of the box. If you can't these, click on the three dots to the right of the column name. 

#### Add a Single Option

- To add your options one at a time, click on the 'add new option' button. This opens a pop-up box where you add the text of your option (in the previous example, the first one would be 'Yes'). 
- Click 'Update' when you have finished. 
- Continue adding all the options you need in this way.

#### Add a Number of Options at Once

- If you have a column based on a field with a number of different options (for example, you could be choosing days of the week) click on 'bulk add option'. 
- Type all your options in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. For example, 'Monday;Tuesday;Wednesday;Not known.'
- When you have finished, click 'add all'. They will appear in a list below the column name.

#### Add from a Built-in List

- Lamplight contains a number of built-in sets of options. To see what is there, click on the 'add from built-in list' button. They include yes/no; some demographic lists such as ethnicity, gender, religion and language; number lists; days and months. If you would like to use any of these lists as options for your column, click on the circle next to the appropriate one then click 'add'. 
- If you do not see any sets of options which are relevant to your column, click cancel to come out of the built-in lists again. 
- Once you have added options to your column fields, don't forget to save them before leaving the page using the 'save all changes' tab which can be found at the top and bottom.

### Changing the Order of Sets, Columns and Options

You can re-order sets, columns and options in the list, which will in turn change the order they are shown in the table. To reorder sets: 

- Find the one you would like to change, click on it, then use the up and down arrows to the right of it to change its position in the list. 
- Alternatively you can reorder all of your sets alphabetically by clicking on the 'sort' button above the list. Pressing this button once will arrange the sets in alphabetical order, while pressing again will sort them in reverse order.

The same principal applies to sorting columns (which can be moved up and down within their set), and options (which can be reordered within the column):

- Click on the column or option that you  want to move, then use the arrow buttons to the right of it. 
- If you want to arrange all columns in a set (or all options in a column) in alphabetical order, use the 'sort' button at the top of the list.

To find the 'sort' button which will order the columns within a set, click on the set name and the sort button will be displayed immediately below it. 

To find the 'sort' button which will arrange options within a specific column, click on the column name, then the button with three dots to the right of it. The 'sort' button appears at the top of the list of options.

### Editing Sets, Columns and Options

You can return to this screen at any time to edit or add sets, columns and options. 

It is best to only edit them to correct typing mistakes or make clarifications. You should not change the meaning of that set/column/option text. 

If you edit a column, be aware that when you change its title this will not change the data that is already stored there. For example, if you changed the options in a 'Passed this module' column, editing 'yes' to 'no' and vice-versa, all your service users who had been recorded as passing the module (by chossing the 'yes' option) would now show as not having done so (as this would have been changed to 'no'), and vice versa. 

To edit the set, column or option:

- Find it in the list and click on the pen and paper icon to the right of it.    
- Make the changes you want, then click 'Update'. Remember to click 'save all changes' at the top of the custom fields page before navigating away, or you will lose any changes you have made.
 
To edit a column option:
 
- Find the column in the list. Click on its name to open the list of options. If you can't see any it could be that this column does not have any options yet, so click on ... (more) button to the right of it to show the 'add options' buttons. 
- Make the changes that you need, then press 'update' on your keyboard to save. Again, remember to 'save all changes' before leaving the page, or you will lose any alterations you've made. 
 
### Deleting Sets, Columns and Options

If you are thinking of deleting tabs, fields or options, be aware that once you do this you will no longer see the information in the attendance table. However, the underlying data has not been deleted, and it is possible in some circumstances for Lamplight to reinstate it for you.

If you delete a set, all of the columns in it will be deleted too. Similarly, if you delete a column the options within that will also be erased.

To delete any set, column or option:
 
 - Find it in the list, then click on the 'dustbin' icon to the right of it. The item you have chosen will now show as pink in the list.
 - Remember to click 'save all changes' at the top or bottom of the page before moving on, or the item will remain active. 




##### Tags
System admin
Activity

###### core module
