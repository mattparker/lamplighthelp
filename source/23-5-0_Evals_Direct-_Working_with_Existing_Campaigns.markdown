# 23.5.0 {{Eval}}s Direct: Working with Existing Campaigns

> Once you have set up a campaign, you can view, edit some settings, or delete it





To see a table of your existing campaigns:
- Go to '{{work}} -> DataDirect -> {{eval}} campaigns -> view'.
- The table here shows you a list of your campaigns. If the one that you are looking for is not in the table, you may need to change the date filters. To do this, click on the 'Filter' button in the 'Search' bar above the table, then choose the dates you need.

### The Search Bar

![DataDirect Search Bar](23.5.0a.png)

The filters in this bar also mean that you can narrow down your results by {{workarea}} and custom fields, and add additional columns.  
  
#### Filtering  

The options allow you to filter: 
   - Between specific dates: set the dates in the 'campaigns are open between' boxes.
   - Related to a particular {{workarea}} or {{subworkarea}}: choose it from the list. If you choose more than one, you will see campaigns which relate to any of the areas chosen rather than to all of them.
   - Related to the staff member who added or edited it last: choose the relevant staff member from the drop-down list.
   - To show deleted campaigns: tick the 'show deleted records' box. If you choose this, no undeleted campaigns will be shown in the table.
   - To show only campaigns using a specific {{eval}}: choose the relevant one from the drop-down list.
- Select the field(s) that you would like to filter the records by. 
- Click the 'Fetch data' button to show records matching these filters.

#### Display Additional Columns

You can also opt to show additional columns in your table.
- Click on these to display names of different {{people}} or {{organisation}}s who have been invited to respond to the {{eval}}.
- Click 'Fetch data' once you have finished to show your results.

### To Change and Save Your Table View

To customise the columns shown in the table:
- Right click in the header row of the table: this will show you a list of all available columns for your table. 
   - Ticked columns are currently visible in the table, and unticked ones are hidden.  
- Click on the item you wish to show or hide. 
- Once you have the table as you want it, you can save it as your default table view. Right click again to bring up the pop-up list, and at the bottom choose 'Save table columns layout'. (If you have added additional columns from the 'Additional data columns to display' view, these can also be saved.) This only affects you, not any other database operators.

Choose 'Reset table columns layout' to return to the default layout.  

### The Context Menu

To bring up a context menu:
- Click on the square to the left of a row, or right click on the campaign you are interested in.  This brings up a number of options:

   ![Campaign Context Menu](23.5.0b.png)

- View full details: shows a summary of the campaign information and settings. 

If you need to find an individual URL for an invitee, right-click on the header row of the invitee table in this view. From this menu, tick the 'Their URL' option and a column will be added to the table showing the individual URL for each person. This only applies if you have opted to send out individual {{eval}}s rather than using the same URL address for all.
   
   ![Their URL](23.5.0d.png)
   
- Edit: edits the campaign information and settings.

You'll see that some items are blanked out: to prevent data inconsistencies you cannot change the {{eval}} template, {{workarea}}, or the separate page option.

In addition, for 'separate page' campaigns, you cannot remove invitees who have already responded: the red cross to delete will not be visible in the invitees table. 

When you have made the changes you want to, click the 'save' button.  They will immediately be 'live' for anyone viewing the survey.

   ![Edit Campaign](23.5.0c.png)


- Delete: deletes the campaign.  You cannot undo this.

You can only delete campaigns that have not had any responses. If you try to delete one that has some replies saved, you will receive an error message. 

If you want to stop an existing campaign, you can edit it to change the 'date to' to the current time and date, which will prevent any more responses. Anyone attempting to respond to it will see an error message. 

- Duplicate record: duplicates the campaign, so that if it is similar to one you are setting up you can alter the details rather than creating one from scratch.

- Email all invitees/have responded/not yet responded: takes you to a {{comm}}s page to email these invitees (for more see [23.3.0 Communicating with Invitees of an {{Eval}}s Direct Campaign](/help/index/p/23.3.0)).

- View report of responses: takes you to an {{eval}}s report (for more see [{{Eval}} Report 15.2.0](/help/index/p/15.2.0)).

### Downloading, Printing and Split Print

If you wish to download the information in the table into a spreadsheet:
- Click the 'Download' button at the bottom of the table.  
- Clicking the print button will open a new tab, with the table in a print friendly format.  
- Split print allows you to create multiple print friendly tables, split by whatever item you choose.

**Please note:** this will only download the table, not the information from individual campaigns. You can download the responses to your campaigns in reporting (see [15.2.0 {{Eval}} Report](/help/index/p/15.2.0)).
   
   
###### datadirect module

