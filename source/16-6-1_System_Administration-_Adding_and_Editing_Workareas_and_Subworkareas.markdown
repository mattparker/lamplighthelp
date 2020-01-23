# 16.6.1 System Administration: Adding and Editing {{Workarea}}s and {{Subworkarea}}s

> In system administration there is a list of the {{workarea}}s you have in your system. You can add to and edit these



{{Workarea}}s and {{subworkarea}}s are managed in a similar way to other lists in system administration (see section [16.6.0 System Administration - Lists](/help/index/p/16.6.0)).

### Things to Consider When Making Changes to {{Workarea}}s

- When a {{work}} record is saved, the {{workarea}} and {{subworkarea}}s selected within that record are saved with it.  
- If you edit the {{workarea}} or {{subworkarea}} in system administration this will change the {{workarea}} or {{subworkarea}} in all the records where the original one was recorded. For example, if you edit Counselling so that it is now Sports, every record that had a {{workarea}} of Counselling will now have one of Sports.  
- If you edit the name, you will no longer be able to use the previous {{workarea}} as a filter for {{report}}s or {{Group}}s. As in the above example, the list of filters for {{report}}s or {{group}}s will show Sports, not Counselling. 
- However, if you run a report showing all {{work}} then choose to present it by {{workarea}} or {{subworkarea}}, the deleted ones will still be shown in the table (providing there is data recorded to show). Ones which have been renamed will only have the new name in the table. (For more on reporting, see [14.0.0 Reporting](/help/index/p/14.0.0), and for {{group}}s see [12.0.0 {{Group}}s](/help/index/p/12.0.0).). 
- You will also not be able to search by your deleted or renamed {{workarea}} when viewing {{activity}} records. 
- For this reason we suggest not removing work areas until the end of your reporting period.
- When you delete a {{workarea}} you are only deleting the category, not any of the historic work records related to it.

{{Workarea}}s are added and edited in the same way as other drop-down lists, but they have another subset ({{subworkarea}}s) to think about. 

### Adding a Single {{Workarea}}
- Go to 'system admin -> Manage Custom Fields and Drop-down Lists -> {{Activity}} Records -> {{Workarea}}s.
- Each existing {{workarea}} is shown in its own coloured box.
- Above these is the option to 'add new {{workarea}}'. Click on this.

![Adding a Single {{Workarea}}](16.6.1a.png)

- In the pop-up box, add the name of the {{workarea}} in the 'Text' box at the top.
- Click on the 'Background colour' box to open the colour-picker, and select the colour you would like to represent this {{workarea}}. (This is what you will see in {{work}} records etc.)
- If you have multiple {{project}}s in your system, you can also choose which ones will share this {{workarea}}. 
- When you have finished, click on 'Update'. 
- If you don't want to add any {{subworkarea}} at this point, don't forget to click the 'save all changes' button at the top or bottom of the page before you leave, or you will lose this new {{workarea}}.
- If you want to add {{subworkarea}}s, see 'Adding {{Subworkarea}}s' below.

### Adding Multiple {{Workarea}}s

It is possible to add a number of {{workarea}}s to this list in one go. 
- Above the list of existing {{workarea}}s, click on the 'bulk add {{workarea}}' button.
- In the pop-up box, type the names of the {{workarea}}s you want to add. Each one should be separated by a semi-colon, but you don't need any spaces between each one. For example 'Breaks;1:1 Counselling;Lunch Club'. 

![Adding Multiple {{Workarea}}s](16.6.1b.png)

- Once you have finished this, click 'add all'. 
- These new {{workarea}}s will appear at the bottom of your list. You will now need to click on the editing icon (a pen and paper)  to open up the details, assign it a colour and decide which {{project}}s it will be available to. For more on this, see 'Adding a Single {{Workarea}}' above. 

![Editing {{Workarea}}s in the List](16.6.1c.png)

- If you don't want to add any {{subworkarea}}s at this point, don't forget to click the 'save all changes' button at the top or bottom of the page before you leave, or you will lose this new {{workarea}}.

![Save All Changes](16.6.1d.png)

- If you want to add {{subworkarea}}s, see 'Adding {{Subworkarea}}s' below.

### Adding {{Subworkarea}}s

Once you have set up your {{workarea}}s, you may want to add {{subworkarea}} 'subsets' to them. For example, you might have 'Advice drop-in' as your {{workarea}}, then 'Benefits and Income Maximisation', 'Housing', and 'Access to Health Services' as your {{subworkarea}}s. This allows you to track and report on your work in more detail.
- Click on the name of the {{workarea}} that you would like to add {{subworkarea}}s to. If it is an existing {{workarea}} you may already see some {{subworkarea}}s listed here.  

**If you're adding one new {{subworkarea}}:**
- Click on 'add new {{subworkarea}}'.

![Adding a New {{Subworkarea}}](16.6.1e.png)

- Type the name of the {{subworkarea}} into the text box.
- Click 'update'. The {{subworkarea}} will now be listed below the {{workarea}}.  

**If you're adding more than one new {{subworkarea}}:**
- Click on 'bulk add {{subworkarea}}'. 
- Type the names of the {{subworkarea}}s you want to add in the pop-up box. Each one should be separated by a semi-colon (;), but you don't need any spaces between each one. For example 'Benefits and Income Maximisation;Housing;Access to Health Services'. 

[Bulk Adding {{Subworkarea}}s](16.6.1f.png)

- When you have finished, click 'add all'. These will now appear in the list below the {{workarea}}.
- Before leaving this page, click the 'save all changes' button at the top or bottom of the page or you will lose your changes.

### Editing {{Workarea}}s and {{Subworkarea}}s

Before editing or deleting {{workarea}}s please see 'Things to Consider When Making Changes to {{Workarea}}s' above. As a general rule, you should only change the name of the {{workarea}} if the meaning is staying the same, for example due to a spelling error or a re-brand. 

- Find the {{workarea}} or {{subworkarea}} text that you need in the list, and click on the paper and pencil symbol to the right of it.

![Editing {{Workarea}}s in the List](16.6.1c.png)

- Make the changes that you need in the pop-up box, then click 'Update'.
- It's possible to add and edit a number of different {{workarea}}s and {{subworkarea}}s on this page, but don't forget to click the 'save all changes' button at the top or bottom of the page before you leave, or you will lose all your changes.


### Moving Items in the List

To the right of each list item is a series of buttons. The first two of these allow you to move an item up and down the list. 

![Up and Down Buttons for System Admin Lists](16.6.1g.png)

If you use the arrows on a {{workarea}}, you will move the {{workarea}} and all its {{subworkarea}}s up and down the list of other {{workarea}}s. If you use the arrows next to a {{subworkarea}}, you will move the {{subworkarea}} up and down within the {{workarea}} that it is associated with. 
- Press the 'up' arrow to move an item up, and the 'down' arrow to move it down the list.
- You can also use the 'sort' button which you will find above the list. Pressing it once sorts your list alphabetically (A-Z), while pressing twice sorts it in reverse order (Z-A).
- Click 'save all changes' at the top or bottom of the page to keep your changes. If you navigate away from this page before saving then all changes will be lost.

### Deleting a {{Workarea}} or {{Subworkarea}}

Before you delete a {{workarea}} or {{subworkarea}} see 'Things to Consider' above. 

You can delete a whole {{workarea}} with all its related {{subworkarea}}s in one go, or choose single {{subworkarea}}s.

- Find the {{workarea}} or {{subworkarea}} in the list. 
- Click on the grey dustbin icon to the right of it. Clicking on the dustbin for a {{workarea}} will also delete all associated {{subworkarea}}s. If you do not want to delete them all, then choose the {{subworkarea}}s individually in the list. 
- The row you have selected will turn red. 

![Delete a {{Workarea}}](16.6.1h.png)

- If you have deleted this in error, clicking on the dustbin icon again will 'undelete' the item.
- Always remember to click 'save all changes' at the top or bottom of the page before you leave. Once you have done this you will not be able to undelete the item.


Why not take a look at our [video demonstration of adding and editing {{workarea}}s and {{subworkarea}}s](/help/index/p/52.4.2) in your system?


###### core module

