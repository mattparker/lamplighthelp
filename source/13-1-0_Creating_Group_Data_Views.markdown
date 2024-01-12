# 13.1.0 <i class="fas fa-binoculars"></i> Creating {{Group}} Data Views

> You can set up as many {{group}} data views as you need in {{Lamplight}}, and each one can be used with any {{group}}. Like {{group}}s, the ones that you create will show in the {{group}} data views table for any database operator on your system to use



To add a new {{group}} data view:

- On the main menu, go to '{{group}}s -> {{group}} data views -> add'.
- The first screen will look like this:

![Adding a {{group}} data view](111a.png)

There are several tabs. Some of the ones you see (for example Evaluations and Communications) will depend on the modules that you have on your system. Apart from the 'View name' tab, you only need to edit the ones which contain information that you want to include in your data view.

**View name:** This is the only tab that you must complete - both the name and description are required fields. When you view the table of data views in the future the name is what you will see, so provide a name that reflects what you're creating and would be clear for others to understand.

**Contact details:** You can select which contact information you'd like to see. Please note that if you use this {{group}} data view to view a table of profiles, the {{person}}/{{org}}'s name will already appear by default so you won't need to include 'First name' or 'Surname' in the data view here as well.

**{{User}} fields, {{Staff}} fields, {{Funder}} fields and {{Contact}} fields:** The information in these tabs relates to the fields in the profile tabs of your {{people}}/{{org}}s. The options within these pages will be unique to your system.

**Relationships:** You can show information in your data view about named individuals/{{org}}s that members of the {{group}} are linked to. Click to select the relationship type you wish to use, and whether you want to see the 'name
  only' of the linked profile, or 'name and contact details'. If you select 'name and contact details for download' you will get the same information as 'name and contact details' but each field is separated by a pipe symbol - | - and
  empty fields are included. This means that if you download the data and do 'text to columns' you'll be able to get the data nicely. However it doesn't look so nice on screen if you just want to see the information in {{Lamplight}}. If you wish to include more than one relationship type, please use the Ctrl button on your keyboard as you select with your mouse. If you select one in error, keep the Ctrl button held down and select again.

**{{Work}}, {{Referral}}, {{Grant}} and {{Outcome}}s tabs:** 
- The 'General summary figures' section at the top of this page lets you produce an overview and/or default date ranges, for example 'total time spent'. Unless mentioned in the option, these aren't dictated by a timeframe and aren't restricted to a {{workarea}}, helpful if you need a general view of records or time spent.
- Further down the page is the 'Detailed summary figures' section which allows you to be more specific about the information you see in your data view. For {{work}} records, for example, you will need to specify which date range you require, what information you want about the records and then how you want to data to be displayed. This will impact how many columns are produced, for example 'just the total number' will create one column, 'show totals split by month' will create a new columnm for each month within the date frame you've specified above. The option 'Every single work record details' will create one column and contain the date, {{workarea}} and {{subworkarea}} of the records, unless you change the default and choose the data you wish to be displayed via the 'Use a template for every single record detail' box. Use the guidance on screen to alter the default settings. Other filters continue down the page, such as {{workarea}} and location, which you can use to filter which records to show and the type of attendance. 

![{{group}} data view - {{work}}](12.1.0d.png)

The example above asks for the number of attendances (number of times involved in a record, if you only need 'attended' please ensure you use the 'attendance type' filter below) within the previous quarter (as Lamplight knows what the present day is this template can be reused each quarter) split by {{workarea}}. If you view a {{group}} using this data view, the result will be a table which has a different column for each {{workarea}} showing the number of attendances in it, as below:

![{{Group}} data view used to view {{group}}](12.1.0e.png)

**{{Comm}}s, {{Eval}}s, {{Linked case}}s tabs:** each of these lets you add summary details about {{referral}}s, {{comm}}s, {{eval}}s, {{grant}}s and {{linked case}}s. Where these relate to a module, you will only see the tab if you have that module switched on in your system.


**Project sharing:** allows you to share the {{group}} data view with other projects. You will need a multi-project set-up and to have access to other projects to see this option.

**Blank column(s):** means that you can add blank columns to your {{group}} data views. You will need a title for each column. This can be useful if you are using {{group}} data views for a sign-in sheet, and you need a 'signature' column, for example. If you wish to add more than one custom column, separate them by using a semi-colon (;) but no space.

When you have added all the information you wish to see, click the 'save' button in the bottom-right of any page.

You can find out more about this in our video, ['How to Create Group Data Views'](help/index/p/52.2.4).

<iframe src="https://player.vimeo.com/video/279244765" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

###### core module

