# 16.12.3 <i class="fas fa-tools"></i> Global Settings: {{Linked Case}}s

> {{Linked case}}s in Lamplight are a way to link different types of work in one place. This tab is where you can turn them on or off, depending on whether you need to use them, and also contains some settings for them


#### Do you want to use {{linked case}}s at all?

{{Linked case}}s in Lamplight are a way to link different pieces of work. A {{linked case}} has a name, description and start and end dates. There are also three types of category that can be used to label {{linked case}}s - you can set these up in system administration. To do this, go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> {{Linked Case}}s. (For more on how to add items to a list in system administration, see [16.6.0 System Administration: Lists](/help/index/p/16.0.0).)

Any {{activity}} record or {{comm}} (if you have the {{comm}}s module) can be added to a {{linked case}}, as well as records which relate to different {{workarea}}s.  For more on this see [9.0.0 {{Linked Case}}s](/help/index/p/9.0.0).

The options for this tab are:

#### Do you want to be able to set open dates of {{linked case}}s manually?

   This option is enabled by default, so the start date of {{linked case}}s can be entered much like it is in {{work}} records. If the start date is always the date the {{linked case}} was entered on the system, or if it's not important to record a start date for a {{linked case}}, disabling this option will make data entry simpler when opening {{linked case}}s.
   
#### Do you want the {{linked case}} tab on profiles?

   The ‘{{Linked case}} view’ tab on profiles allows you to see all the active and inactive {{linked case}}s in a profile, and all the records linked to them. You can also create new {{linked case}}s and link records to them here. If you are not using {{linked case}}s in this way, you can turn off this profile tab using this option. It is still possible to access {{linked case}}s through the main menu at '{{work}} -> view -> {{linked case}}s.
   
#### If so, you can specify a custom template for the "unlinked records" button here

   If you have the {{linked case}} tab enabled on profiles (see option above), there is a button above the list of {{linked case}}s that shows all records not included in a {{linked case}}. You can specify what details appear on this button using the codes outlined in the menu. In the case below we show the number of records on the button:
   
   These buttons act as summaries of the {{linked case}}, so these templates can be used if you need to see different information about each at a glance.  When you click on the buttons the full details of the {{linked case}} are loaded and shown.
   
   ![The Unlinked Records Button](16.12.3a.png)
   
   In the global settings page it looks like this:
   
   ![Global Settings for Unlinked Records Button](16.12.3b.png)
 
#### Custom template for the open {{linked case}} buttons

   As with the option above, you can choose details to appear on the open {{linked case}} buttons. You will need to have set up a custom template for unlinked records for this to take effect (see above). The one we have set up here shows the case name, ID number, the number of records in the case and the total time taken on it to date:
   
   ![The Open {{Linked Case}} Button](16.12.3c.png)
   
   The set-up for this in global settings looks like this:
   
   ![Global Settings for Open {{Linked Case}} Button](16.12.3d.png)
   
#### Custom template for the closed {{linked case}} buttons

   As with the two options above, you can choose what is shown on the closed {{linked case}} buttons. Again, you will need to have set up the custom template for unlinked records for this to take effect (see above). In the example below, we have chosen to show the name, ID number and date of closure of the case:
      
   ![The Closed {{Linked Case}} Button](16.12.3e.png)
   
   The set-up for this in global settings looks like this:
   
   ![Global Settings for Closed {{Linked Case}} Button](16.12.3f.png)
   
#### Only allow {{Linked case}}s to be created within the tab on a profile?  

   You can create {{Linked case}}s from within the ‘{{Linked case}} view’ tab on a profile or via an {{activity}} record that is not yet linked to a {{Linked case}}. 

   Ticking ‘Only allow {{Linked case}}s to be created within the tab on a profile?’ in system admin disallows the option of creating a {{Linked case}} via an {{activity}} record. This means that every {{Linked case}} opened will be linked to a profile in the system, as every {{Linked case}} will have to be opened via a profile’s ‘{{Linked case}} view’ tab, and so prevents having {{Linked case}}s in the system that are not linked to a profile.

   #### Include {{Linked case}}s that were created in other profiles?

   This field gives three different options for which profiles {{Linked case}}s appear in or if they appear in the profile ‘{{Linked case}} view’ tab at all. 
   
   There are three options to choose from. 
   
1.	‘Both: show a {{Linked case}} if it was opened in the profile, or this profile attended an {{activity}} connected to the {{Linked case}}’ – the {{Linked case}} will appear in the profile it was opened in AND any profile that is listed in the attendance table of any {{activity}} record linked to the {{Linked case}}. 
2.	‘Only show {{Linked case}} in a profile if they were opened in that profile’ – the {{Linked case}} will only appear in the profile it was opened in. 
3.	‘Only include {{Linked case}}s via listings on {{activity}} records’ - {{Linked case}}s will not appear in any profile but are only listed in the '{{activity}} > view > {{Linked case}}s listing.

   
###### core module
