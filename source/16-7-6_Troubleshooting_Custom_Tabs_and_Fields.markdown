# 16.7.6  <i class="fa fa-cogs"></i> Troubleshooting Custom Tabs and Fields

> If you have a question about editing or are having an issue with one of your custom tabs or fields, you can find the answer to common queries here




### What happens when I edit an existing field?  

   It is best to only edit fields or options to correct typing mistakes or make clarifications. If you have any data in the field you should not edit it to change the meaning. This is because the data already stored in the system does not change; it is only the label which is altered. For example, if you change the options in a 'gender' field, editing 'male' to 'female', all your service users whose genders are already recorded as 'male' will now show as 'female'.

### If I delete a custom tab or field, does that delete the data too?  

   No, if you delete a tab or field then the data is still stored in the system, but you will not see it in profiles and you will not be able to choose it to report on. For example, if you have created a group/list data view using the field ‘support need’ but have since deleted this field, when you run a data view which was previously set up to include ‘support need’, this field will still show in the table.
   
### Can I change the field type without losing my data?  

We do not recommend that you do this. You need to be careful about what you change it from and to.  There are some types of field which do translate well:  
      
   - if you have a single-select field which you change to a multi-select, Lamplight will be able to read the information and this will transfer without a problem. (This does not work the other way around - if you change a multi-select field to a single-select field then for any multi-responses already recorded only the first item selected will show in the field.  
   -	if you change a small text field to a larger one, this just changes the box size and the text is undisturbed.
   - date type fields can be changed to other date type fields, although 'year' fields may cause problems.


Issues happen when the type of information you are recording is changing. For example, if you change a free text field to a number box, Lamplight will not be able to read the original information in the same way, so any data the has been inputted to that time will not show.

[Linking or unlinking existing fields](/help/index/p/16.7.1) with data in them will also cause problems and should be avoided.
   
### I've set up a new tab/field, but I can't see it when I look at a profile. Where's it gone?  

   This could be down to a couple of things:
   
   - When you initially set up a new tab or field, you need to specify which type of profiles it will appear on, and for what roles. In the dialogue box when you are adding a new tab or field you will see:
   
      ![Type of Person and Role in Custom Tabs and Fields](16.7.6a.png)
      
      You can only choose one ‘person’ type, but to select multiple ‘roles’ for a tab or field, hold down the ‘Ctrl’ key as you click items in the list. This has to be completed for both the tab and each field in it. When you look on the tab and field management page, you can see what person type and role have been selected for each one.
      
      In the example below that the ‘Personal Details’ tab is visible to individuals who are users, staff, contacts and volunteers. The ‘Gender’ field in that tab is visible to people who are users:
      
      ![Type of Person and Role Showing on Tab and Field Lists](16.7.6b.png)
      
      The tab / field will only appear in the types of profile you choose. If, for example, it is set up to be for clients, you will not see it in a staff profile.
      
      If the correct person or role types are not showing, click on the paper and pen icon to the right of the tab or field name) to edit and update the settings. Remember to click on 'save all changes' at the top of the custom fields page before you leave, or you will lose any alterations you have made. 
   
   - If you have already selected [which tabs to view in your personal settings](help/index/p/16.4.2), you will need to tick any newly created tabs before they will be visible in profiles.
   
   ![Selecting Tabs to View in Personal Settings](16.7.6c.png) 
 
   
##### Tags
System admin
Top tips

###### core module



   


