# 16.7.4  <i class="fa fa-cogs"></i> Adding and Editing Custom Tabs and Fields to {{Work}} and Other Records

> It is possible to add additional tabs and fields to your {{work}}, {{referral}} and other {{activity}} records through system administration





In the system administration menu page, there is a section called 'Manage Custom Fields and Drop-down Lists'. This is where you'll find options for adding and managing custom fields and tabs to different types of {{activity}} record.

![System Admin Adding Custom Fields to {{Activity}} Records](16.7.4b.png)

Each type of record works on the same principle, with the example below being for {{work}} records.  The process is almost identical to adding custom tabs and fields on profiles.  


### Tabs, Fields and Options in {{Work}} Records

- Go to 'Manage Custom Fields and Drop-down Lists -> {{Work}} Records Custom Tabs and Fields -> Manage custom tabs and fields on {{work}} records'.

- If you already have tabs set up in your system, you will see a list showing them all. You can click on any one of these to see the fields that are held in that tab.

- If you find that there is too much information on the screen and that you would like to see a simpler view, click on the 'compact view' button the middle of the page above the list. Click on it again to revert to the standard view. 

![System admin - Adding custom fields to records](16.7.4a.png)


### Creating a New Tab

Above the list there are two buttons which you can use for adding new tabs - 'add new tab', which allows you to add tabs one at a time, and 'bulk add tab' which you can use if you are adding a number of new tabs. 

#### Adding a Single Tab

- Click on 'add new tab'. This opens a pop-up box where you can fill in the details:
   - Text: this will be the tab name.
   - {{Project}}s: you can select which {{project}}s this tab will apply to (if you have more than one {{Lamplight}} {{project}}).
   - xxxxxxx You may also see fields about publishing, if you have the Publishing Module.  See section [28.0.0 Publishing Module](/help/index/p/28.0.0)
- When you have finished, click 'Update'. Remember, the new tab is not finally saved until you have clicked 'save all changes' at the top or bottom of the main custom tabs page.  
   
![System Admin - Tab Information](1219a.png)

#### Bulk Adding Tabs

- Click on 'bulk add tab'. This opens a pop-up box.
- Type all the names of all the tabs that you are adding in the text box, separated by a semi-colon (;). You do not need a space before each one. For example, 'Support Issues;Situation Update'.
- When you have finished, click 'add all'. Don't forget, these are not finally saved until you click on the 'save all changes' at the top or bottom of the page before exiting. 
- You will now see all your new tabs at the bottom of the list. 
- If you want to make them available to other {{project}}s, or to add publishing options, click on each one individually and choose the pen and paper icon to open it for editing. This will be the same as described for a single tab above.
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) You are now ready to add the fields to your tab.


### Adding Fields

- Click on the tab that you would like to add fields to. If there are already fields in this tab you will see them listed here. If it is  a new tab you will see the option to click to add a new field. 

#### Adding a Single Field

- Either click the 'add new field' button which is above the list of existing fields, or, if it is a new tab, click the 'add new field' to get started button in the tab itself.  This opens up a pop-up box. Complete the details with:

![Adding a new field](16.7.2f.png)

   - Field name: this is the text of the field that you will see.
   - Required field?: if you choose this option it will not be possible to edit the tab and save it without putting data in this field.
   - Placeholder text: this will appear in your empty text box (for example 'Add the reason here') if you choose that field type.
   - Descriptive text: this can be shown below the field as an explanation (for example 'only complete this if the previous answer was 'no').
   - The type of field required: for advice on which type of field to choose see [16.7.3 Custom {{Work}} and Other Record Tabs and Fields](/help/index/p/16.7.3).
   - If you have more than one {{project}}, you have the option to share this new field across them.
   - If you have the Publishing Module, you can also specify whether data in this field should be published. See [28.1.0 Publishing Module Security](/help/index/p/28.1.0) for more information about the Publishing Module and the controls in place.
 - When you have completed all the details, click 'Update'. Remember, this will not be finally saved until you click 'save all changes' at the top or bottom of the {{work}} record custom fields page. 
- The field that you have just added will now appear in the tab.

#### Bulk Adding Fields

- Click on 'bulk add option' beneath the header of the tab you would like to include them in. This opens a pop-up box.
- Type the names of all the fields that you are adding in the text box, separated by a semi-colon (;). You do not need a space before each one. For example, 'Consent;Sign-up for Newsletter;Ready to Volunteer'.
- When you have finished, click 'add all'. Don't forget, these are not finally saved until you click on the 'save all changes' at the top or bottom of the custom fields page before exiting. 
- You will now see all your new fields at the bottom of the list. 
- Click on each one in turn and choose the pen and paper icon to open it for editing. Their names will already be entered into the form, but you will need to add additional details for them, such as type of field, as described for a single tab above.
- When you've finished editing each one, click 'Update'. (Again, you still need to click on 'save all changes' before exiting the page.) When you have added all the details you can add options to your fields, as necessary. 

#### Adding Fields to a Standard System Tab

All records have the tabs 'Where and Where', 'Attendance', (this may be called 'Respondent' or 'Involved' in some cases), and Details.  You can't edit of delete the fields which already exist in these tabs (this can only be done by Lamplight), but you can add additional fields to them by 'creating' them in System Admin.  Create a tab with the correct name as below, (capitalisation is essential), and add fields to it.  

![System Admin - adding fields to system tabs](1221a.png)

#### {{Work}} records

- When and where
- Attendance
- Details

#### {{Outcome}} records

- When and where
- Respondent (if you have this tab)

#### {{Referral}} records

- When and where
- Attendance (if you have this tab)
- Involving (if you have this tab)
- details

#### {{Grant}} records

- When and where
- Attendance
- details


### Setting Options
   
The field that you have just added may need some options (for example, if it is a 'Current status' single-select field, you might want the options 'Active' and Inactive'.) If you created it as a single field, it will already be open with buttons allowing you to add options at the bottom. If it is an existing field that you want to add more fields to, or are editing, click on the field name then select the three dots on the right to see these 'add' options. 

#### Add a Single Option

- To add your options one at a time, click on the 'add new option' button. This opens a pop-up box where you add the text of your option (in the previous example this would be 'Active'). 
- Click 'Update' when you have finished. 
- Continue adding all the options you need in this way.

#### Add a Number of Options at Once

- If you have a field which provides a number of different options, click on 'bulk add option'. 
- Type all your options in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. For example, 'Active;Inactive;Not known.'
- When you have finished, click 'add all'. They will appear in a list below the field name.

#### Add from a Built-in List

- Lamplight contains a number of built-in sets of options. To see what is there, click on the 'add from built-in list' option. They include yes/no; some demographic options such as ethnicity, gender, religion and language; number lists; days and months. If you would like to add any of these lists of options to your field, click on the circle next to the appropriate one then click 'add'. 
- If you do not see any sets of options which are relevant to your field, click cancel to come out of the bulk lists again. 

Once you have added options to your fields, do not forget to save them before leaving the page, using the 'save all changes' tab which can be found at the top and bottom. 


### Changing the Order of Tabs, Fields and Options

You can re-order tabs, fields and options in the list, which will in turn change the order they are shown in the rest of Lamplight. To reorder tabs: 

- Find the one you would like to change, click on it, then use the up and down arrows to the right of it to change its position in the list. 
- Alternatively you can reorder all of your tabs in alphabetical order by clicking on the 'sort' button above the list. Pressing this button once will arrange the tabs in alphabetical order, while pressing again will sort them in reverse order.

The same principal applies to sorting fields (which can be moved up and down within their tab), and options (which can be reordered within the field):

- Click on the field or option that you  want to move, then use the arrow buttons to the right of the one you want to move. 
- If you want to arrange all fields in a tab (or all options in a field) in alphabetical order, use the 'sort' button at the top of the list.

To find the 'sort' button which will order the fields within a tab, click on the tab name and the sort button will be displayed immediately below it. 

To find the 'sort' button which will arrange options within a specific field, click on the field name, then the button with three dots to the right of it. The 'sort' button appears at the top of the list of options.


### Editing Tabs, Fields and Options

You can return to this screen at any time to edit or add tabs and fields. 

It is best to only edit fields or options to correct typing mistakes or make clarifications. You should not edit fields or options if you change the meaning of that field/option text. 

If you edit a field, be aware that when you change the title of a field this will not change the data that is already stored there. For example, if you changed the options in a 'gender' field, editing 'male' to 'female' and vice-versa, all your service users whose genders had previously been recorded as 'male' would now show as 'female', and vice versa. 

To edit the tab or field:

- Find the required tab or field in the list and click on the pen and paper icon to the right of it.    
- Make the changes you want, and click 'Update'. Remember to click 'save all changes' at the top of the custom fields page before navigating away, or you will lose any changes you have made.
 
To edit a field option:
 
- Find the field in the list. Click on its name to open the list of options. If you can't see any it could be that this field does not have any options yet, so click on ... (more) button to the right of it to show the 'add options' buttons. 
- Make the changes that you need, then press 'enter' on your keyboard to save. 
 

### Deleting Tabs, Fields and Options

If you are thinking of deleting tabs, fields or options, be aware that once you do this you will no longer be able to filter, present information in reports, or create data views using any information already entered into them. However, the underlying data has not been deleted, and it is possible in some circumstances for Lamplight to reinstate it for you.

If you delete a tab, all of the fields in it will be deleted too. Similarly, if you delete a field, the options within that will also be erased.

To delete any tab, field or option:
 
 - Find it in the list, then click on the 'dustbin' icon to the right of it. The item you have chosen will now show as pink in the list.
 - Remember to click 'save all changes' at the top or bottom of the page before moving on, or the item will remain active.

 
##### Tags
Activity

###### core module

