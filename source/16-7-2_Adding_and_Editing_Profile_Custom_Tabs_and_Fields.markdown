# 16.7.2  <i class="fa fa-cogs"></i> Adding and Editing Profile Custom Tabs and Fields

> Profile information for {{people}} and {{org}}s, for example demographics, is captured with custom tabs and fields



{{Lamplight}} enables you to set up and customise the tabs and fields that appear on profiles. You can have as many of these as you need to capture different information. Different types of profile will have their own custom tabs. 

### Finding Your Profile Tabs

- Go to admin on the menu bar and click 'system administration'.
- Under the 'Manage Custom Fields and Drop-down Lists' section, click on 'Manage custom tabs and fields on profiles'.
- If you already have tabs set up in your system, you will see a list showing them all. You can click on any one of these to see the fields that are held in that tab.
- If you find that there is too much information on the screen and that you would like to see a simpler view, click on the 'compact view' button the middle of the page above the list. Click on it again to revert to the standard view. 

![Setting up custom fields and tabs](16.7.2a.png)

### To Add a New Tab
   
- Above the list there are two buttons which you can use for adding new tabs - 'add new tab', which allows you to add tabs one at a time, and 'bulk add tab' which you can use if you are adding a number of new tabs. 

![Add a New Tab](16.7.2b.png)

#### Adding a Single Tab

- Click on 'add new tab'. This opens a pop-up box where you can fill in the details.
   - 'Tab name' is the name that you will see at the top of the tab.
   - Type of {{person}} - you must choose what type or types of {{person}} this new tab is for. If you do not choose anything here then the new tab will not be visible on any profiles.
   - Roles - you can also choose to limit this tab to {{people}}, {{org}}s or {{family}} (if they are used in your system) with particular roles.
   - Restrict the field - ticking this means that only operators with a Manager or Administration level of access will be able to see the field and its contents.
   - {{Project}}s - if you have more than one {{project}} in your system, you can choose to share this tab so that it is also visible in other {{project}}s. When tabs and fields are shared, it is possible to report information across {{project}}s.
- Once you have finished, click the 'Update' button in the bottom right corner. 

![Completed Tab Information](16.7.2c.png)

- The new tab you’ve added will now appear at the bottom of the list. It will be open, allowing you to add the fields to it that you need (for instructions see 'Adding Fields' below).


#### Bulk Adding Tabs

- Click on 'bulk add tab' button. This opens a pop-up box.
- Type the names of all the tabs that you are adding in the text box, separated by a semi-colon (;). You do not need a space before each one. 

![Bulk Add Tab](16.7.2d.png)

- When you have finished, click 'add all'. 
- You will now see all your new tabs at the bottom of the list. 
- You will need to add in the details of the tab, as described for adding a single tab above. To do this, click on the pen and paper icon to the right of the name . You will need to add the details for them as described for a single tab above (name, role etc).
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) You are now ready to add the fields to your tab.

### Adding Fields
   
- Click on the tab that you would like to add fields to. If there are already fields in this tab you will see them listed here. If it is  a new tab you will see the option to click to add a new field. 

#### Adding a Single Field

- Either click the 'add new field' button which is above the list of existing fields, or, if it is a new tab, click the 'add new field to get started' button in the tab itself.  This opens up a pop-up box. Complete the details with:
   - The 'Field name' (this is the text you will see next to the field in the new tab).
   - Whether it is a required field (if you choose this option it will not be possible to edit the tab and save it without putting data in this field).
   - Placeholder text, which will appear in your empty text box (for example 'Add the reason here') if you choose that field type.
   - Descriptive text which can be shown below the field as an explanation (for example 'only complete this if the previous answer was 'no').
   - Which type of profiles it will be applicable to (both the type of {{person}} and the role). It is important that you fill these in, or the field will not be visible in any profiles.
   - The type of field required - there is detailed information on how to choose the best field type in [16.7.1 Custom Fields in Profiles](/help/index/p/16.7.1).
   - Whether to restrict the field to Managers and Admins. If you select this it means that database operators with lower levels of access will not see these fields or be able to add data to them.
   - If you have more than one {{project}}, you have the option to share this new field with other {{project}}s.
   - If you have the Publishing Module, you can also specify whether data in this field can be published - although you will also need to authorise this for each individual profile before any data becomes available. See [28.1.0 Publishing Module Security](/help/index/p/28.1.0) for more information about the controls.
   - When you have completed all the details, click 'Update'. Remember, this will not be finally saved until you click 'save all changes' at the top or bottom of the profile custom fields page. 
- The field that you have just added will now appear in the tab.
  
 ![New Field in Tab](16.7.2e.png) 
 
#### Bulk Adding Fields

- Find the field and click on 'bulk add option' either beneath the header, or if it is a new tab, in the tab itself. This opens a pop-up box.
- Type the names of all the fields that you are adding in the text box, separated by a semi-colon (;). You do not need a space before each one. For example, 'Consent;Sign-up for Newsletter;Ready to Volunteer'.
- When you have finished, click 'add all'. Don't forget, these will not be finally saved until you click 'save all changes' at the top or bottom of the page before exiting. 
- All your new fields will now appear in the tab (if you can't see them, click on the tab name or the three dots icon to the right hand side for more). 
- Open each one in turn to add the details (to do this choose the pen and paper icon to the right to open it for editing). 

![Editing Fields](16.7.2f.png)

- Their names will already be entered into the form, but you will need to add the other details for them, such as type of field, as described for a single tab above.
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) When you have added all the details you can add options to the fields that need them. 

### Setting Options
   
The field that you have just added may require some options (for example, if you've added a 'Current status' field, you might want the options 'Active' and Inactive'.) If it's a field that you have just added it you will see buttons allowing you to add options. If it is an existing field that you are editing, click on the field name then select the three dots ('more' button) on the right to see these 'add' options. 

![Adding Options](16.7.2g.png)

#### Add a Single Option

- To add your options one at a time, click on the 'add new option' button. This opens a pop-up box where you add the text of your option (in the previous example this would be 'Active'). 
- Click 'Update' when you have finished. 
- Continue adding all the options you need in this way.

#### Add a Number of Options at Once

- If you have a field which provides a number of different options, click on 'bulk add option'. 
- Type all your options in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. For example, 'Active;Inactive;Not known.'
- When you have finished, click 'add all'. They will appear in a list below the field name.

#### Add from a Built-in List

- Lamplight contains a number of built-in sets of options. To see what is there, click on the 'add from built-in list' button. They include yes/no; some demographic options such as ethnicity, gender, religion and language; number lists; days and months. If you would like to use any of these lists as options for your field, click on the circle next to the appropriate one then click 'add'. 
- Once they've been added to a field they behave like any other options, and you can edit them and add more if needed.

![Built-in List Options](16.7.2h.png)

- If you do not see any sets of options which are relevant to your field, click cancel to come out of the bulk lists again. 

Once you have added options to your fields, do not forget to save them before leaving the page, using the 'save all changes' tab which can be found at the top and bottom of the page. 

#### Linked Fields

You may want to link fields together so that you can enter multiple records under a single field (for more on this see [16.7.1 Custom Fields in Profiles](/help/index/p/16.7.1)). Remember, if you do this you will not be able to use the data in the linked fields for reporting, creating {{group}}s or {{group}} data views. This is most suitable for historic information you need to hold but do not need to report on, such as previous addresses or notes that are required for day-to-day work which do not need to be analysed or filtered.

- Create the fields you wish to link, making sure that they are next to each other in the tab and in the correct order. 
- Looking at the first field that you are linking, click on the squared button to the right of it. An information box will appear, explaining about linked fields, then giving the option at the bottom to 'create new linked record set'.  Click on this. This first field will now have been added to the linked set. 

![Creating a Linked Field](16.7.2i.png)

- Click on the next option that you want to add to the set. Another box will pop up explaining again about linked fields, and asking if you want to create a new set, or link to the first option that you just added to a set. Click the 'Link with previous record set' option. You will see that these now both have a coloured bar to the left of them, and a link symbol to show that they are in a set. 

![Creating a Linked Field Set](16.7.2j.png)

- Continue adding options in the same way until all the fields that you want are linked to one another. 
- If you link an option in error, click the squared icon again to get the option to 'Remove this field from the linked set'.
- Once you have saved your changes using the 'save all changes' button at the top of the custom fields page, press F5 to refresh your system. When you look at the fields in the tab, you will now see that they are displayed as a table rather than separately.

You can create several groups of linked fields on the same tab. These links are indicated by the number displayed next to the squared icon on each option, and the colour of the bar to the left of the fields. Each field can only be included in one 'linked field' set. 

### Changing the Order of Tabs, Fields and Options

You can re-order tabs, fields and options in the list, which will in turn change the order they are shown in the rest of Lamplight. To reorder tabs: 

- Find the one you would like to change, click on it, then use the up and down arrows to the right of it to change its position in the list. 

![Up and Down Arrows in a List](16.7.2k.png)

- Alternatively you can reorder all of your tabs alphabetically by clicking on the 'sort' button above the list. Pressing this button once will arrange the tabs in alphabetical order, while pressing again will sort them in reverse order.

The same principal applies to sorting fields (which can be moved up and down within their tab), and options (which can be reordered within the field):

- Click on the field or option that you  want to move, then use the arrow buttons to the right of it. 
- If you want to arrange all fields in a tab (or all options in a field) in alphabetical order, use the 'sort' button at the top of the list.

To find the 'sort' button which will order the fields within a tab, click on the tab name and the sort button will be displayed immediately below it. 

To find the 'sort' button which will arrange options within a specific field, click on the field name, then the button with three dots to the right of it. The 'sort' button appears at the top of the list of options.

### Editing Tabs and Fields

You can return to this screen at any time to edit or add tabs and fields. 

It is best to only edit fields or options to correct typing mistakes or make clarifications. You should not edit them if you change the meaning. 

If you edit a field, be aware that when you change its title this will not change the data that is already stored there. For example, if you changed the options in a 'gender' field, editing 'male' to 'female' and vice-versa, all your service users whose genders had previously been recorded as 'male' would now show as 'female', and vice versa. 

To edit the tab or field:

- Find it in the list and click on the pen and paper icon to the right of it.    
- Make the changes you want, then click 'Update'. Remember to click 'save all changes' at the top of the custom fields page before navigating away, or you will lose any changes you have made.
 
To edit a field option:
 
- Find the field in the list. Click on its name to open the list of options. If you can't see any it could be that this field does not have any options yet, so click on '...' (the more button) to the right of the name to show the 'add options' buttons. 
- Make the changes that you need, then press 'update' on your keyboard to save. Again, remember to 'save all changes' before leaving the page, or you will lose any alterations you've made. 
 
### Deleting Tabs, Fields and Options

If you are thinking of deleting tabs, fields or options, be aware that once you do this you will no longer be able to filter, present information in reports, or create data views using any information already entered into them. However, the underlying data has not been deleted, and it is possible in some circumstances for Lamplight to reinstate it for you.

If you delete a tab, all of the fields in it will be deleted too. Similarly, if you delete a field, the options within that will also be erased.

To delete any tab, field or option:
 
 - Find it in the list, then click on the 'dustbin' icon to the right of it. The item you have chosen will now show as pink in the list.
 
 ![Deleting Items in Custom Tabs and Fields](16.7.2l.png)
 
 - If you have deleted in error, just click the dustbin icon again and the row will return to the normal colour.
 
 - Remember to click 'save all changes' at the top or bottom of the page before moving on, or the item will remain active. 

We also [have a video](/help/index/p/52.4.3] which shows you how to add, edit and order custom tabs and fields in your system.


##### Tags
System admin

###### core module

