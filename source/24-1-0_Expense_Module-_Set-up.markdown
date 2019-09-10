# 24.1.0 Expense Module Set-up

> There are two areas to set up in System Administration to support the adding of expenses to the system: cost status items and cost categories

Configuring these settings needs System Administrator level of access. 

If you have the Expense Module, when you add a new {{work}} or other {{activity}} record you will see an 'Expenses' tab. There is a table in this tab, and one of the columns is called 'Status'. This is where you set different categories so that you can see where an expense claim is up to (for example, 'waiting for receipt'). There is also a column headed 'Category' where you can add categories which allow expenses to be differentiated to help with reporting (for example 'travel', 'accommodation' and 'training'). How you choose to classify both of these things is up to you.

Settings are added, edited and deleted in the same way. 

### To Find Cost Status Items and Cost Categories  

- Go to ‘admin -> system administration' and find the 'Module Administration' section.
- In the 'Expenses Module' box, click on  either 'Cost status items' or 'Cost categories'.

![Adding Categories to the Expenses Module](24.1.0c.png)

- For cost status items by default, {{Lamplight}} has three categories - ‘Expense Incurred’, 'Authorised' and 'Paid'. Additional status items can be added to this list. 

### Adding, Editing and Deleting List Items

### Adding a List Item  

- The final option in the list will always be ‘double-click to add’. Double-click this text to create a new blank list item. 
- Type the name and save by pressing 'enter' on your keyboard. 
- Your item will be added, and the ‘double click to add’ link will reappear at the bottom of the list.
   
### Editing a List Item  

- Double-click the text of the list item that you would like to edit.
- This will open up a text field which you can edit. 
- Once edited, press ‘Enter’ on your keyboard to save it.
   
### Deleting a List Item  

- Click on the item you no longer need and drag it to the grey box at the bottom which says ‘Drag here to delete’. 
- The item will appear in the grey box, confirming that it is being deleted. 
**Please note:** It is not possible to delete a list item that has just been created without first leaving the page. If you see the  ‘Unable to delete item’ error message, click back to the system administration menu then return to the editing page.
   
### Changing the List Order  

- Change the order of the list by left-clicking an item and dragging it to its new position before releasing. 
- The other items will adjust to make space for it.

### Location Costs  

The costs of using locations can also be calculated if hourly rates are already assigned to them. To assign rates:

- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists', and click on 'Locations'.
- Click ‘add contact details’ under the name of the location.

![Adding Costs to a Location](24.1.0a.png)

- Scroll to the bottom of the dialogue box to find the ‘Hourly rate (for internal purposes)’ field.

![Hourly Rate Boxes](24.1.0b.png)

- Put the hourly rate into this field.
- Click the ‘save’ button. 
- Once an hourly rate has been added to a location, whenever the location is used, the costings module will add a cost per hour for its use.

For more on setting up Locations see [52.1.1 How to Add and Edit Locations](/help/index/p/52.1.1).

**Please note:** Locations are not only used for costing purposes in {{Lamplight}} - your organisation may be using them to view the diary or to filter your activity information. Please be aware of other users when thinking about adding, editing or deleting any locations in your system. 


###### costs module






