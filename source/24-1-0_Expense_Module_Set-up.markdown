# 24.1.0 Expense Module Set-up

> There are two areas to set up in System Administration to support the adding of expenses to the system: cost status items and cost categories



Configuring these settings needs System Administrator level of access. 

If you have the Expense Module, when you add a new {{work}} or other {{activity}} record you will see an 'Expenses' tab. There is a table in this tab, and one of the columns is called 'Status'. This is where you set different categories so that you can see where an expense claim is up to (for example, 'waiting for receipt'). There is also a column headed 'Category' where you can add categories which allow expenses to be differentiated to help with reporting (for example 'travel', 'accommodation' and 'training'). How you choose to classify both of these things is up to you.

Settings for status items and cost categories are added, edited and deleted in the same way. 

### To Find Cost Status Items and Cost Categories  

- Go to ‘admin -> system administration' and find the 'Module Administration' section.
- In the 'Expenses Module' box, click on either 'Cost status items' or 'Cost categories'.


### Adding, Editing and Deleting List Items

#### Adding a List Item  
- The items currently in the list will show in boxes on the page. Above these are 'add new item' (to add a single item) and 'bulk add item' (to add a number of items) buttons. 
**If you are adding a single item:**
   - Choose 'add new item', then type the name of the item in the 'Text' box.
   - Click 'Update'. You will see it added to the list.
   - Click 'save all changes' at the top or bottom of the main page to keep this change. (You can make a number of changes on the same page without saving in between, but you must not navigate away from the page before saving or all the changes will be lost.)
**If you are adding a number of items:**
   - Choose 'bulk add item', then type in each of the items separated by a semi-colon (;). You do not need spaces between each one (for example 'Pending further checks;Waiting for receipt'.
   - When you have listed them all, click 'add all'. You will see them added to the list - check that they are all as you expected.
   - Click 'save all changes' at the top or bottom of the main page to keep these items.

#### Editing Existing Items
Before making any changes, we recommend that you only ever edit existing items if there is a spelling or other mistake in the name, or if you are changing to something with an equivalent meaning. Changing the name of a category in the list can also affect your data, as although the name will be different, the data already recorded in that category will still be there. If, for example, you rename the 'Waiting for receipt' option to ‘Manager to authorise’, every expense previously listed as an ‘Waiting for receipt’ will now show as a 'Manager to authorise' which would affect your processes. You should never edit existing items if you change the meaning of the item: better to add a new item with the different meaning.

There are also some items in the list that are standard to the {{Lamplight}} system, and are used for specific calculation and reporting purposes within your system. Although it is possible to edit these items and change their names, they will always retain their original meaning, so any changes should retain the original meaning for these items.  (There is a warning label on any such items).

![Warning for List Item with Particular Meaning](24.1.0d.png)

- In system admin, find the list that you item is in.
- Find the relevant item in the list, and click on the pen and paper icon ('edit text') to the right of it. 
- Make the changes you need, then click 'Update'.
- Click 'save all changes' at the top or bottom of the page to keep your changes. If you navigate away from this page before saving then all changes will be lost.

![Editing lists](144a.png)

#### Re-ordering Items Already in the List
- To the right of each list item is a series of buttons. The first two of these allow you to move an item up and down the list.
- Press the 'up' arrow to move an item up, and the 'down' arrow to move it down the list. 
- You can also use the 'sort' button which you will find above the list. Pressing it once sorts your list alphabetically (A-Z), while pressing twice sorts it in reverse order (Z-A). 
- Click 'save all changes' at the top or bottom of the page to keep your changes. If you navigate away from this page before saving then all changes will be lost.

#### Deleting an Item
- Find the item you would like to delete in the list.
- Click the grey dustbin icon to the right of it. This will turn the selected row red. 
- If you have clicked this in error, clicking on the dustbin icon again will 'undelete' the item.
- Click 'save all changes' at the top or bottom of the page to keep your changes. Once you have done this you will not be able to undelete the item.

### Location Costs  
The costs of using locations can also be calculated if hourly rates are already assigned to them. To assign rates:

- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists' find the 'Work Records' box and click on 'Locations'.
- Click on the location in the list that you would like to add an hourly rate to, then click the pen and paper icon to the right of it.

![Adding Costs to a Location](24.1.0a.png)

- Scroll to the bottom of the dialogue box, then add the hourly rate in the ‘Hourly rate (for internal purposes)’ field.
- Click the ‘update’ button. 
- Remember to click on 'save all changes' at the top of the main page before exiting, or your alterations will be lost.  

Once an hourly rate has been added to a location, whenever the location is used the costings module will add a cost per hour for its use.

**Please note:** Locations are not only used for costing purposes in {{Lamplight}} - your organisation may be using them to view the diary or to filter your activity information. Please be aware of other users when thinking about adding, editing or deleting any locations in your system. 


###### costs module






