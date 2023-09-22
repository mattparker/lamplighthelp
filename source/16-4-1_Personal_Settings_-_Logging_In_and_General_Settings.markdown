# 16.4.1 <i class="fas fa-tools"></i> Personal Settings - Logging In and General Settings

> This section allows you to customise what you see on your home screen, what information you show on the 'my {{user}}s' tab, your colour-scheme, some options of how tables are displayed, whether you are warned about timeouts, as well as how you view form data



'Logging in and general settings' is the first section in personal settings. When you make any change you should scroll to the bottom of this screen and click save. You should then refresh your system (F5 on a windows computer, command – R on a Mac) to see the changes take effect.

#### Home Page Tabs

   Use these checkboxes to choose which tabs you want to see on your home page. 

   ![Home Page Tabs in Personal Settings](16.4.1a.png)
    
   You can also left click on a box and drag it to change the order in which it appears. While the order shows as top to bottom in personal settings, it is left to right on your home page. 
   
   ![Tabs on the Home Page](16.4.1b.png)

   Operators who are not system administrators can also opt to force the "news" tab to always appear as the last tab. The news tab
is used by {{Lamplight}} to let you know about system changes, training coming up, and other information about your system. When there
is an unread news item, by default the tab will appear as the first tab on the home page. Once you've marked the item as "read", the
tab will revert to being the last tab on the home page.

If you choose to limit the news tab to being the last tab in the system, you may miss updates from {{Lamplight}}. We don't post 
news very frequently, and we don't recommend that you do this. However we know that the home page changing unexpectedly can be a problem
for some people, and so we've given you the option to do this.

System admins do not see this option because we need to be able to update you on changes to the system.

#### Template to Use on Diary Items

   This can change what basic information you see on your homepage diary. By default you will see the beginning and end time of each record in the diary, and information taken directly from the ‘summary’ box in the work record. You can add in more information by choosing from the template strings under the box, for example {location}. 

   Each separate string is shown in {}. If you are adding these to the diary template, you may want to separate each with a colon or dash or other text. So if, as in the example above, you were adding in ‘location’, the text in your ‘Template to use on diary items’ box would look like this:
   
<code>{start_time} - {end_time}:  {SUMMARY}: {location}</code>

   And when looking at a record in your diary, it would show like this:

   ![Home Page Diary](16.4.1c.png)

   If you want information to show in the diary, you will need to ensure you are recording it in your work records. 

#### {{Group}} Data View to Use on My {{User}}s Home Page Tab

   Use this drop-down list to select a {{group}} data view you would like to apply on your ‘My {{User}}s’ home page tab. This will customise the information that appears in the table of that tab. 
   For example, if you have a data view showing address details, and choose to use that to view your ‘my {{user}}s’ table, it would look something like this:

   ![My Clients Tab](16.4.1d.png)

#### Colour Scheme

   Use this drop-down list to select a different colour scheme for {{Lamplight}} if you would like. There are a few set colour schemes available to you.  

   Your colour scheme will not change until you refresh the page.

#### Date and time formatting

Use these drop-downs to select your preferred date and time formats.

There are a handful of places within the system where the default formats (day/month/year and hours:minutes) are used and cannot be changed for technical
reasons.

There are examples in the drop-downs for the different format options, but the letters used in the formats are:
 - d = two digit day of the month
 - m = two digit month of the year
 - Y = four digit year
 - jS = digit day of the month plus suffix (e.g. 22nd)
 - H = two digit hour (24 hour clock)
 - i = two digit minutes
 - s = seconds
 - g = hours (12 hour clock)
 - a = am or pm


#### Use 'Sticky Titles' That Always Appear on Screen When You Scroll Down

   If you use a header bar on your profiles (see [13.2.3 Using a Data View to Create Headers](/help/index/p/13.2.3)) selecting this option will mean that it stays at the top of the screen as you scroll down, and you continue to see the information wherever you are in the profile.

#### Show a Menu Button on Tables

   Selecting this option makes the menu button on the left of any table visible.
   If the option is not ticked, your work table will look like this:

  ![Tables Without a Menu Button](16.4.1e.png)

   If you do tick this option (and save your settings) your work table will now be showing the menu button:

  ![Tables With a Menu Button](16.4.1f.png)

   If you choose not to show menu buttons you can still access table menu options by right clicking on the relevant row.
   After you have saved changes to this option, refresh your browser for the changes to take effect.

#### Show {{Linked Case}} Options on Context Menus

   If you use {{linked case}}s, tick this box to include options relating to them on context menus.  
   If you do not choose to do this, when you are viewing the menu for a {{work}} record your options will look like this:

   ![Context Menus Without {{Linked Case}} Options](16.4.1g.png)

   If you select this option your menu will also display options related to {{linked case}}s, as shown below: 

   ![Context Menus With {{Linked Case}} Options](16.4.1h.png)

   Refresh your browser for changes to take effect.

#### Use a Confirm Box to Warn of Timeouts

   {{Lamplight}} will log you out after 20 minutes of inactivity by default (i.e. if you have not been navigating through {{Lamplight}}, saving or editing records. The System Administrator can change this amount of time, so you could find that it is longer or shorter on your system. If you choose this option, {{Lamplight}} will bring up a warning to let you know when you are about to be logged out, giving you the opportunity to save your work. The pop-up warning box looks like this:

   ![Timeout Warning Box](16.4.1i.png)
 
#### Show Keyboard Shortcuts

   Use this drop-down if you would like to be able to use keyboard shortcuts to navigate around {{Lamplight}}. Once you have selected one of these options a number or letters will appear on tabs: use alt+[option] on the keyboard to navigate to this tab without using the mouse.
 
   ![Keyboard Shortcuts](16.4.1j.png)
 
   Refresh your browser for the changes to take effect.
   

#### Open Pop-ups In
 
    There are a number of places in {{Lamplight}} that use pop-up windows, for example when you are viewing an existing record. Choosing 'new browser window' from this drop-down will open the record in a new browser rather than pop-up. 

#### Use Tabs on Forms

   By default, {{Lamplight}} shows forms such as {{work}}, {{referral}} and {{outcome}} records split into separate tabs. If you untick this box, when you go to enter a new {{work}} record, instead of seeing it across a number of tabs it will appear as one long form.
With this box checked your {{work}} record appears like this:

   ![{{Work}} Record With Tabs](16.4.1k.png)

   With the box unchecked there are no tabs at the top:

   ![{{Work}} Record Without Tabs](16.4.1l.png)

   Refresh your browser for any changes to take effect.


##### Tags
Time saving tips

###### core module
