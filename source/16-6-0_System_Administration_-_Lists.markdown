# 16.6.0  <i class="fa fa-cogs"></i>  System Administration - Lists

> Managing drop-down lists in system administration allows you to add, edit and delete {{workarea}}s, {{outcome}}s, {{linked case}} categories, relationship types and {{referral}} success categories. You may also have some related to the modules that you have in your system, for example communications or multimedia.



There are a number of drop-down lists which exist in {{Lamplight}}. These can all be added to and edited in the same way. (We also have specific guidance on [{{workarea}}s](/help/index/p/16.6.1), [{{outcome}}s](/help/index/p/16.6.2) and [relationships](/help/index/p/16.6.3).) 

### Important Things to Consider When Making Changes to Existing List Items
When you make changes to a drop-down list, it can have an effect on your existing data.  It’s very important to consider this before you start.
- If you delete an item from a list, this will remove the item from the existing list and it will no longer be possible to see if it was selected. For example, if you delete the 'parent/child' relationship, this will no longer be visible in the profile of anyone who was previously recorded as a 'parent' or 'child'.
- Changing the name of a category in a list can also affect your data, as although the name will be different, the data already recorded in that category will still be there. If, for example, you rename the 'Attendance type' option ‘Cancelled’ to ‘Booked’, everyone previously listed as ‘Cancelled’ in a {{work}} record will now show as 'Booked'.  This would affect your reporting and your view of completed activities.  You should never edit existing items if you change the meaning of the item: better to add a new item with the different meaning.

#### Finding the Relevant List
- Go to 'admin -> system admin -> Manage Custom Fields and Drop-down Lists'.
- Click on the list you would like to alter.
- Alternatively, if it is a dropdown list relating to a module, you can find this in the 'Module Administration' section of system admin. 

#### Adding New Items to a List
- The items currently in the list will show in boxes on the page. Above these are 'add new item' (to add a single item) and 'bulk add item' (to add a number of items) buttons.

![Adding New Items to Lists](16.6.0a.png)

If you are adding a single item:
  - Choose 'add new item', then type the name of the item in the 'Text' box.
  - Click 'Update'. You will see it added to the list.
  - Click 'save all changes' at the top or bottom of the page to keep this change. (You can make a number of changes on the same page without saving in between, but you must not navigate away from the page before saving or all the changes will be lost.)
   
![Save All Changes](16.6.0c.png) 

If you are adding a number of items:
  - Choose 'bulk add item', then type in each of the items separated by a semi-colon (;). You do not need spaces between each one.
  - When you have listed them all, click 'add all'. You will see them added to the list - check that they are all as you expected.
  - Click 'save all changes' at the top or bottom of the page to keep these items.

#### Editing Existing Items
Please read 'Important Things to Consider' (above) before making any changes.
- In system admin, find the list that you item is in.
- Find the relevant item in the list, and click on the pen and paper icon ('edit text') to the right of it. 

![Editing lists](16.6.0b.png)

- Make the changes you need, then click 'Update'.

- Click 'save all changes' at the top or bottom of the page to keep your changes. If you navigate away from this page before saving then all changes will be lost.

#### Re-ordering Items Already in the List
- To the right of each list item is a series of buttons. The first two of these allow you to move an item up and down the list.

![Moving Items Up and Down a List](16.6.0d.png)

- Press the 'up' arrow to move an item up, and the 'down' arrow to move it down the list. 
- You can also use the 'sort' button which you will find above the list. Pressing it once sorts your list alphabetically (A-Z), while pressing twice sorts it in reverse order (Z-A). 

![Sorting Items in a List](16.6.0e.png)

- Click 'save all changes' at the top or bottom of the page to keep your changes. If you navigate away from this page before saving then all changes will be lost.

#### Deleting an Item
Please read 'Important Things to Consider' (above) before deleting any list items.
- Find the item you would like to delete in the list.
- Click the grey dustbin icon to the right of it. This will turn the selected row red. 

![Deleting List Items](16.6.0f.png)

- If you have clicked this in error, clicking on the dustbin icon again will 'undelete' the item.
- Click 'save all changes' at the top or bottom of the page to keep your changes. Once you have done this you will not be able to undelete the item.

Why not have a look at our [video on how to manage drop-down list items in system admin](/help/index/p/52.4.1)?


##### Tags
System admin

###### core module

