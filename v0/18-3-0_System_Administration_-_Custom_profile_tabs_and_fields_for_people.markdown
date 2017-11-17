# 18.3.0    System Administration - Custom profile tabs and fields for {{people}}

> {{Lamplight}} enables you to set up and customise the tabs and fields that appear on profiles. 

{{Lamplight}} enables you to set up and customise the tabs and fields that appear on profiles. 

To do so, click on 'view add and edit tabs and fields on profiles' in the system administration menu. If you are doing this for the first time, you will see a fairly blank screen:

![Setting up custom fields and tabs]({{imgpath}}146a.png)

The left-hand panel lists the tabs currently set up. The central panel will list the fields available in a particular tab. The right-hand panel will show details for a particular field within a tab.

If you have already set some tabs and fields up, there will be more buttons displayed in the left- hand column. Each button represents a tab.

The tabs and fields are very flexible. You decide whether a tab applies to {{people}}, and also based on their role. So you can have different tabs for {{user}}s that are individuals and {{user}}s that are organisations. And you can have the same, or different, tabs for people who are {{user}}s and people who are members of {{staff}}.

To add a new tab, click on the 'click to add' button. The central panel will display a 'blank' tab:

![Adding a new tab]({{imgpath}}146b.png)

To add the tab, double- click on the 'Tab label: click to add' text. A pop-up window will appear, allowing you to set the basic details of the tab.

__Important__  If you set-up a new tab, and then leave System Administration witout entering at least one field, the tab will appear on your system, but will not be available to populate in the System Administration menu.  To fix this you will need to contact Lamplight.  Always add a field to a new tab, even if only a temporary one, which you can remove later when others are added.

![Setting the tab name]({{imgpath}}146c.png)

Give the tab a name (this is what will appear on the tab in the profile). Select who this tab should appear for, and if you have multiple {{project}}s, you can choose which {{project}}s the tab will be available for. Click the 'save' button in the bottom right hand corner. The main page will update itself, showing the information you have just entered.

You will now need to add some fields to the tab, and you need to do this now.  If you navigate away from this screen now, without adding any fields, you'll be stuck with a tab that is visible in profiles but which you can't edit. If a tab does not have any fields in it, it will not be displayed here. To add a field, click the 'click to add' button in the central panel for the tab you wish to add the field to.

The right-hand panel will now show a 'blank' field. To add the field, double-click the text 'Field name: click to add'. A popup window will appear:

![Adding a new field]({{imgpath}}146d.png)

This window is similar to adding a tab, with two extra options: Type and Is this a required field. The field types available are:

  * Select box - Select a single option from the list of options.
  * Multi-select box - to select several options, hold the ctrl key down and select the options you need.
  * Plain text area - enter a short amount of free text.
  * Plain text box - enter longer amounts of free text
  * Rich text - enter free text here and add formatting as desired.
  * Check box - click on the box to fill in a tick
  * Radio button - click on the button to indicate a yes
  * Dates - Dates are entered in UK format by selecting from the day/month/year select boxes or using the popup calendar.
  * Date/Times - Dates and times are entered on a 24 hour clock from select boxes.
  * Date of birth selector - Dates are entered in UK format by selecting from the day/month/year select boxes and a current age is displayed.
  * Number box - enter numbers only into a small text box.
  * Caption - a label is added, to separate fields within a tab.
  * Fixed text box - again this is descriptive text that cannot be altered in profiles, but can be used to add descriptive text or reminders about the other information on the tab
  * Year selector - choose the year from a drop-down (but not month or day)
  * Radio buttons - select one: add several radio buttons, only one of which can be selected
  * Checkboxes - select many: lets you select several options using tick boxes
  * Charity number lookup - enter a Charity Commission registered number and {{Lamplight}} will add a link to their page on the Charity Commission website
 * Twitter name: a text box that will let you look up their recent tweets
  * Web address - for additional websites - and will provide a link to the site

If you specify a field as 'required'. It would result in anyone wishing to add information to the persons profile to complete this field before navigating away from the page. 

Click the 'save' button when you have entered the information needed. The third panel will update showing the information added. Restricting a field to managers or admins means that database operators with lower levels of access will not see these fields or be able to add data to them. If you have the publishing module enabled, you can also specify whether data in this field should be published - although the profile needs to be published as well before any data becomes available. See [24.1.0  Publishing module security](/help/index/v/{{version}}/p/24.1.0) for more information about the publishing module and the controls in place.

If your field is a 'select box' or 'multi select box' you can now add the options that will appear in the drop-down. Double click the 'click to add' button

![Adding options]({{imgpath}}146e.png)

and a popup window will appear where you enter the text that should appear in the select list. If you wish to add a list of options in one go, type all the options (separated by a semi-colon) and then click add.

![Adding the option text]({{imgpath}}146f.png)

Repeat this process until you have added all the tabs, fields and options that you require.

You can re-order tabs, fields and options by dragging them to the required position. Hold the mouse cursor over the button representing the tab/field/option you want to move, click and hold the left mouse button, and move the tab/field/option up or down the list until it's in the right place. Let go of the mouse button and the tab/field/option will drop into position and the new order will be saved.

Most of the time your fields will have a single value that doesn't change (unless you enter an incorrect value by mistake!). For example, a person only has one date of birth, and this will never change. In some other cases you may need to be able to enter multiple records under a particular field. For example, you may need to be able to enter multiple text entries describing medical conditions as a person's medical condition changes. You may also need to be able to {{group}} a set of records together - in this example you may need a 'date diagnosed' field, a 'description of condition' field, and a medication 'field', all linked together. On the profile, this would be displayed as a table:

![Adding linked fields]({{imgpath}}146g.png)

To create these links between fields, first create the fields you wish to link on the same tab, and make sure that they are next to one another in the correct order. Next, select them. To do this, click and hold the left mouse button to the left of the first field in the {{group}} you wish to create. A small red rectangle will appear. Still holding the left mouse button down, move the mouse so that the red rectangle covers all the fields you wish to link together:

![Adding linked fields part 2]({{imgpath}}146h.png)

The backgrounds of the fields being linked will change colour. When you have selected all the fields you want to link together, release the left mouse button. When you do this the links will be saved, and the background colours change to show this.

You can create several groups of linked fields on the same tab. This links are indicated by the different background colours of the fields.

You can return to this screen at any time to edit or add tabs and fields. If you edit a field, be aware that this will change all existing data for this field. For example, if you changed the options in a 'gender' field, editing 'male' to 'female' and vice-versa, all your service users' genders would change. It is best to only edit fields or options to correct typing mistakes or make clarifications. You should not edit fields or options if you change the meaning of that field/option text. 

[View the video](/help/video/id/39)
###### core module

