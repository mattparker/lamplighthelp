# 29.1.0 {{Staff}} Management Module: Set-up

> Before using the {{Staff}} Management Module you will need to set up a {{staff}} hierarchy and list items which enable you to specify absence, training and other categories


You’ll need to have a System Administrator role to update the list items and organise the {{staff}} hierarchy (this governs who can see {{staff}} profiles). The list items allow you to customise the options available when adding absence, training and appraisal records.

### Managing the {{Staff}} Hierarchy  

Due to the potentially sensitive nature of the data held within the {{Staff}} Management Module (pay details, annual leave etc), {{staff}} profiles are governed by a hierarchy. By default, the only person who can see the {{staff}} management information in a profile is the database operator themselves. The hierarchy then allows some people to see (and report) on others. 

- Go to the 'admin -> system administration'.
- Toward the bottom of this page is the 'Module Administration' section. In this section find teh '{{staff}} Module' box.
- Click on 'View and edit {{staff}} hierarchy’.
- This will open a list containing all the people who have a ‘{{staff}}’ profile in {{Lamplight}}. This is not limited to database operators. 

![{{staff}} Hierarchy](29.1.0d.png)

- To set the hierarchy, click, hold and drag the person who is managed, over the name of the person who is their manager and release your mouse.

   - Scenario 1 - Joseph Bloggs manages Arlene Gee.
   Left click, hold and drag the name ‘Arlene Gee’ over the top of ‘Joseph Bloggs’ and release the mouse. Joseph Bloggs can now see the {{Staff}} Management Module tabs of his own profile AND Arlene Gee. Arlene Gee, Hermione Granger and Jolly Jepson can only see their own profiles.

![{{staff}} Management Scenario 1](29.1.0a.png)

   - Scenario 2 - Joseph Bloggs manages Arlene Gee and Jolly Jepson.
   Left click, hold and drag the name ‘Jolly Jepson’ over the top of ‘Joseph Bloggs’ and release the mouse. Joseph Bloggs can now see the {{Staff}} Management Module tabs of his own profile AND Arlene Gee AND Jolly Jepson. Arlene Gee, Hermione Granger and Jolly Jepson can only see their own profiles.
   
![{{staff}} Management Scenario 2](29.1.0b.png)

- Scenario 3 - Arlene Gee manages Hermione Granger.
  Left click, hold and drag the name ‘Hermione Granger’ over the top of ‘Arlene Gee’ and release the mouse. Joseph Bloggs can now see the {{Staff}} Management Module tabs of his own profile AND Arlene Gee AND Jolly Jepson AND Hermione Granger. Arlene Gee can now see the {{Staff}} Management Module tabs of her own profile AND Hermione Granger. Hermione Granger and Jolly Jepson can only see their own profiles
 
![{{Staff}} Management Scenario 3](29.1.0c.png)

### Adding Items to {{staff}} Management Lists

There are a number of customisable lists in the {{Staff}} Management Module which allow you to add items such as reasons for absence and training categories. Items in each of these lists are treated in the same way in system administration. 

To add items to these:
- In system administration, find the '{{Staff}} Module' (see above).
- In this box you will see a number of options:

[{{Staff}} Module List Options](29.1.0e.png)

- Each one of is a list of categories for the {{Staff}} Module, and you can work through them so that you have the options you need when adding information. 

For more on adding options to lists in system administration, see [16.6.0 System Administration: Lists](/help/index/p/16.6.0).

**Non-contact Work**  

Please note, if you need to add a new {{workarea}} to be used in your non-contact {{work}} records, please add these as standard {{workarea}}s. You can then ask us to assign them specifically to non-contact {{work}} records.

### Global Settings

There are also a couple of options in Global Settings relating to how timesheets are handled. To set these:

- Go to 'admin -> system administration.'
- In the 'Customise Lamplight' box, click on 'Change global settings'. 
- Go to the '{{Staff}} module' tab.
- In here you will see 3 options:

![{{Staff}} Module Global Settings](29.1.0f.png)

   - Show timesheets combined across {{project}}s: if you choose this option, then {{Lamplight}} will take time logged in {{work}} records across all {{project}}s into account rather than just the one that you are in. This is only relevant if you have more than one {{Lamplight}} {{project}}.
   - Include records in timesheet for which {{staff}} had attendance type(s): you decide whether you only want to include records in the timesheet where {{staff}} have attended, or whether other attendance types should also be taken into account. To pick more than one role press Ctrl and click. 
   - Include records in timesheet for which {{staff}} members had attendance role(s): this can be useful where a member of {{staff}} is also a {{volunteer}} or a {{user}}. You can restrict the records which count to towards the timesheet so that they only relate to times when they are listed as {{staff}}, or you can choose to include all records, regardless of their role, in the timesheet. To pick more than one role press Ctrl and click. 


###### staff module
