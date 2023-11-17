# 16.6.2  <i class="fa fa-cogs"></i> {{Outcome}}s

> {{Outcome}}s in your system are organised so that you have a main {{outcome}} category and {{outcome}} measures within each of these categories


Adding, editing and deleting {{outcome}}s works in the same way as for other lists, except that you have a main {{outcome}} category and {{outcome}} measures within each category. 

You can have as many categories as you need, and each can have any number of {{outcome}} measures in it. For practical reasons we'd generally suggest no more than ten measures in each category. 

If you wish to you can add "descriptors" for each possible score in each measure. These will help your team and your 
clients to understand what each score means. For example, if you have a scale of 1 - 5, you might want to add a 
descriptor for each score, such as "1 = very unhappy" and "5 = very happy".

If you are using an established {{outcome}} framework (e.g. Core, WEBWMS, Outcome Stars) these can be imported 
directly into your system without having to enter all the details. In many cases sub-totals and totals, and 
descriptions for individual scores, will also be set up for you.  Please contact Lamplight through the Hub if you'd 
like to do this before entering them manually into your system.

Before you change or delete an {{outcome}} you need to consider the implications. These are the same as for {{workarea}}s - for more on this see [16.6.1 Adding and Editing {{Workarea}}s and {{Subworkarea}}s](/help/index/16.6.1)).

### A Note on Copyright

Some established outcome frameworks are protected by copyright and the owners of those rights may require you to 
have a license before you may use their materials. If you are using an established framework, however it is added to 
the system, please ensure that you have the necessary permissions to use it.

We have a partnership with Triangle Consulting who produce the Outcome Stars. If you wish to use an Outcome Star you 
will need to speak with Triangle first, and they will then let us know and we'll set up the Outcome Stars that you 
need in your system for you. If you need any help or further information about this please contact us through the Hub.


### To Add a New {{Outcome}}

- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> {{Outcome}}s -> {{Outcome}} measures'.
- You will see the existing {{outcome}}s listed on this page. 
- Above the list of {{outcome}}s are the 'add new {{outcome}} category' button, which you can use to add one {{outcome}} category at a time, and the 'bulk add {{outcome}} category' button, which is for adding a number of categories at once.

![Adding {{Outcome}} Categories Buttons](16.6.2a.png)

#### Adding a Single {{Outcome}} Category

- Click on 'add new {{outcome}} category'. This opens a pop-up box.
- Enter the name of the category in the 'Text' box and, if you have {{project}}s in your system, choose which of them will be able to see and use this set of {{outcome}} measures.
- Click 'update' to add the new category to the list. Remember, the changes are not final until you have clicked 'save all changes' at the top or bottom of the page.
- Your new category will now open at the bottom of the list, ready to add measures to - see below.

#### Bulk Adding {{Outcome}} Categories
This can be useful if you are adding a number of {{outcome}} categories at once.
- Click on 'bulk add {{outcome}} categories'. This opens a pop-up box.
- Type the names of all the categories you need to add in the text box, each one separated by a semi-colon (;). You do not need to put spaces between categories. 

![Adding {{Outcome}} Categories in Bulk](16.6.2b.png)

- Press 'add all' when you've finished. Remember, no changes are finally saved until you have clicked 'save all changes' at the top or bottom of the page.
- Your new categories have now been added to the bottom of the list. If you have a multi-{{project}} set up you'll need to click on the 'edit' icon to the right of each one to assign what {{project}}s it is visible to. Otherwise you can start to add the individual measures to the categories - see below.

![Editing {{Outcome}} Categories](16.6.2c.png)

### To Add Measures/Questions to an {{Outcome}}

- If you have added a single {{outcome}} category it will open automatically so that you can add measures to it. If you have bulk added categories you will need to find the one that you would like to add measures to in the list, then click on it to open. 

**Adding a Single {{Outcome}} Measure**

- Click the 'add new {{outcome}} measure' button. This opens a pop-up box.

![Adding a Single {{Outcome}} Measure](16.6.2d.png)

- Type in the text for your measure in the 'Text' box.  
- Choose the 'Measure type' from the list:

   - **'score'**: Choose this if you're using a scale system (for example a scale of 1-10) to record your {{outcome}}s (e.g. "how confident do you feel about job-seeking, where 10 is very and 1 is not at all?")
   - **'yes/no'**: Choose this if the measure is a simple yes/no (e.g. "in full time employment").
   - **'number'**: This is for recording specific amounts (for example, "by how much has your debt been reduced?" - from 50,000 to 0).
   - **'scores with user specified issue'**: As well as recording a score, the first time you enter data, you have a 
     text box to record exactly what the issue is. The next time you will see the previously entered issue text and 
     can just update the score. There are some limitations with these measure types - please see below.

- Minimum and maximum values: Use these to set your lowest and highest score for the measure (e.g. as above, your scale might be 1 (minimum) and 10 (maximum)). If you're creating a yes/no {{outcome}} use the minimum value of 0 and the maximum value of 1.
- 'Notes': Double click to open the notes section to add any explanatory notes for operators. These appear when you add the {{outcome}} either through {{activity} -> add new -> {{outcome}}, or if you go to the {{outcome}} tab in a profile then click the 'add' button. You will not see it if you choose to add the {{outcome}} through the profile tab, using the 'add' button in the Mode box in the middle of the page. 
- Show scores without descriptors. If you don't add descriptors for every single score, do you still want to be able 
  to record those scores? For example if your scale is 1 - 5 and you only add descriptors for 1 and 5, do you still 
  want people to be able to enter a '3'?
- The data entry type is how scored outcomes are presented to the people entering data. See below for examples of 
  the different options for these.
- If you are using emoji style for data entry, you can opt whether to also include the text on screen. Note that the 
  descriptor text is always added as "alt" text to assist screen readers.
- How much change (in score) is considered meaningful is a threshold for the system to use when calculating 
  progress. For example, if you set this to 2, then a change of 1 will not be considered meaningful, but a change of 
  2 or more (positive or negative) will be. This is used in the aggregate reporting where you can filter to see results 
  that are above this threshold. Clearly any change is meaningful to the people experiencing it, this is a 
  statistical tool to assist in your analysis. If you leave this as 0 then all results will always be included, and 
  if you don't know what to put in this box, we suggest leaving it as 0.
- If you have more than one {{project}}, you can tick which {{project}}s you would like this measure to be available to.

![New {{Outcome}} Measure Pop Up](16.6.2e.png)

- Click 'update' when you have finished. Remember that these changes will not be finally saved until you click 'save all changes' at the top or bottom of the page.

**Adding Multiple {{Outcome}} Measures**

If you have more than one measure to add to a category, you can also opt to put the measures in together, then edit each one to add the detail. To do this:

- Click on 'bulk add new {{outcome}} measures.
- Enter the measures in the text box, each one separated by a semi-colon. If you choose to add them in this way, you'll need to find each one in the list and edit it (click on the pen and paper icon to the right to open the editing box) to include the type, values and notes, as we saw with the single measure before. 

![Editing Icon](16.6.2f.png)

- Continue these steps until you have added all the measures that you need.

#### Scores with user specified issue

This measure type is intended to be used where you want to record a score, but also want to record what the issue is.
One option is to create a set of different measures, one for each type of issue, and recording the detail in the 
comments box. However this can feel prescriptive and may not be appropriate for your situation. It can also lead to 
a long list that becomes hard to navigate.

The measure type "scores with user specified issue" allows you to record the score and the issue in one place. The 
first time you enter data for a particular {{user}} you will be prompted to enter the issue. The next time you enter
data for that {{user}} you will see the previously entered issue and can just update the score.

A downside of this is that it means that when reporting in aggregate you will be combining different types of 
issue. One person may make progress in self-confidence while another in their housing situation: when reporting 
overall you will see that two people made some progress on 'Issue 1'. Using separate measures would allow you to see 
the progress on each issue separately.

Another limitation is that you can only enter this data through the particular tab for the {{outcome}} category in 
their profile. This is because each person's issue will be different.  So when setting up these measures, you will 
need to add the additional tab to profiles in 
[personal settings](https://lamplight.online/en/admin/settings/what/allsettings) -
see [16.4 Personal settings](/help/index/p/16.4) for help with this.



### Data entry types for different measures

Information on how to add and update descriptors is given in the sections below. This explains how your choices of 
the measure will affect the data entry options once the descriptors are set up.

- For Score measures with no descriptors set, the data entry will be a numerical text field - type in a number to save
  the value.
- Yes / no measures are always shown as select boxes with the options "Yes" and "No"
- Number measures are always added as a numerical text field.
- If you select "a range of values using different emoji as the main data entry" you can select a different emoji
  for each score (as in the slow-fast example). You can only select one image to represent the score when entering data.
- If you select "a star-rating style using a single emoji" then the expectation is that each score has the same
  emoji - though they don't have to be stars. When you click on the third star (say), the first and second wiil be
  highlighted. While you could use different emoji for each score, they would all 'light up' when selected and in
  most cases would be confusing to users.
- Score measures with descriptors but no emoji will be displayed as a select box with the descriptors as options.

The examples below illustrate the different options.

![{{Outcome}} Descriptors](16.6.2m.png)

The "User specified issue" in the example shows an additional text entry box for the first time the score is entered.
This is where the user would say what the issue that they want to address is. The next time they enter data for this
measure, they will see the text they entered previously and can just update the score.

The "score emoji with different emoji" measure has also opted to display the text for each option, and you can see 
the size labels below each image.

The size you specify for each emoji is the size of the image relative to the surrounding text. In most cases you are 
likely to want these to be the same for each descriptor, and either 2x or 3x is likely to be appropriate. 




### Adding Score Descriptors

Sometimes you may want to show descriptors for your {{outcome}}s - this is text which describes what the score for this measurement means. These only really make sense with 'score' type measures. For example, you may have a scale of 1 - 5 where 1 is 'very unhappy' and 5 is 'very happy'. You can add these descriptors to your scores so that they show when the {{outcome}}s are being recorded. (You will only see this when you add the {{outcome}} either through {{activity} -> add new -> {{outcome}}, or if you go to the {{outcome}} tab in a profile then click the 'add' button to the right of the page.)  

![{{Outcome}} Descriptors](16.6.2g.png)

You will not see it if you choose to add the {{outcome}} through the profile tab, using the 'add' button in the Mode box in the middle of the page. 

- Find the measure that you would like to add descriptors to, and click to open it. 

#### To add a single descriptor:
- Click on 'add new score descriptor'. A pop-up box will open.
- Enter the score which you are describing in the top box. For example, '1'.
- In the box underneath write what the score means, for example 'Very unhappy'. 
- If you wish to use emoji-style data entry, enter it here. On Windows you can press the Windows key and the period key to open the emoji picker. On Mac you can press Control + Command + Space to open the emoji picker.
- Select the size you require for the emoji, relative to the regular text around it. Double or 3x is likely to be 
  appropriate.

![Single Score Descriptor](16.6.2hh.png)

- Click 'update' when you have finished.

#### To add a number of descriptors to the same measure:
As with categories and measures, it's possible to bulk add descriptors too.
- Click on 'bulk add score descriptor'. This will open a pop-up box.
- Add the descriptors that you need, each one separated by a semi-colon (;). You do not need a space at the 
  beginning or end of them. It's easier if you add these in order from the lowest score to the highest.

![Bulk Adding Score Descriptors](16.6.2i.png)

- Click on 'add all' when you have finished. This will add all the descriptors to your measure. 
- Look down the list and check that they all have the correct score allocated to them. If not, you can edit them individually (by clicking on the pen and paper icon).

![Checking {{Outcome}} Score Descriptors](16.6.2j.png)

#### If you 

- Once you have finished, don't forget to click 'save all changes' at the top of bottom of the page.

### Editing {{Outcome}}s
Before you make any changes to your categories or measures, you need to be aware of the implications of editing an {{outcome}}. For more on this see 'Things to Consider' in [16.6.1 System Administration: Adding and Editing {{Workarea}}s](/help/index/p/16.6.1).

- To edit a category or measure, click on it in the list, then click the paper and pencil icon to the right of it. 
- Make the changes. 
- Click 'Update'. Remember, these changes will not be finalised until you click 'save all changes' at the top of bottom of the page. 

### Changing the Order of {{Outcome}}s, Measures and Descriptors

It is possible to change the order in which your {{outcome}}s are listed. To do this: 
- Go to the one you would like to change and use the up and down arrows to the right of it to change its position in the list. 
Alternatively you can reorder all of your {{outcome}}s in alphabetical order by category name.
- Above the list of {{outcome}}s, click on 'sort'. Pressing this button once will arrange the {{outcome}}s in alphabetical order, while pressing again will sort them in reverse order. 

![Checking {{Outcome}} Score Descriptors](16.6.2k.png)

The same principal applies to sorting measures and descriptors. If you want to move them up and down the list, use the arrow buttons to the right of the one you want to move. If you want to arrange them in alphabetical order, use the 'sort' button at the top of the list.
- To find the 'sort' button which will order the measures within an {{outcome}}, click on the relevant category name so that all the measures are listed below it. The 'sort' button is at the top of this list of measures. 
- To find the 'sort' button which will arrange descriptors for a specific measure, click on the name of the measure, and the 'sort' button appears at the top of the list of descriptors.

### Deleting {{Outcome}}s
Before you delete an {{outcome}} you need to be aware of the implications. For more on this see 'Things to Consider' in [16.6.1 System Administration: Adding and Editing {{Workarea}}s](/help/index/p/16.6.1).

- You can delete either a whole {{outcome}} category, or specific measures within a category.  
- To delete the whole category, including measures, click on its name in the list, then click the 'bin' icon to the right. This will turn the category red in the list. 

![Deleting an {{Outcome}} Measure](16.6.2l.png)

- To delete an individual measure within a category, click on the category name so that you can see the list of measures, then click on the 'bin' icon to the right of the one that you need to delete.
- To delete a descriptor, click on the name of the measure that the descriptor is listed under, then click on the 'bin' icon to the right of the one you need to remove.
- Always remember to click on 'save all changes' at the top or bottom of the page before exiting for your changes to take effect. If you exit the page without saving then all your changes will be lost.


###### core module

