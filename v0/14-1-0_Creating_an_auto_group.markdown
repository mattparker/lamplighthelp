# 14.1.0    Creating an {{auto group}}

> On the main menu go to {{Group}}s -> Add -> Add {{auto group}}. Give the {{group}} a name and description; enter your search criteria, and click 'Save'. 

On the main menu go to {{Group}}s -> Add -> Add {{auto group}} and you will see the following screen:

![Creating an {{auto group}}]({{imgpath}}103a.png)

**{{Group}} name tab**: The first thing that you need to do on this screen is to give your {{group}} a name and a description.  Choose something that makes it clear who your {{group}} is made up of as these fields are used to remind you and other users of what the {{group}} is for. Both are required fields. There is also a tick box to allow you to 'lock' the group. This means that only you will be able to edit the {{group}} once it has been created.

There is a 'Lock {{group}} option here.  This allows you to lock the {{group}} so that only you can change the {{group}}.  This can be useful for example, when creating a regular {{group}} for reporting, where you need to be absolutely certain that the group criteria has not been changed bwteen running it.  Only you will be able to change or delete this group.  We suggest using this cautiously.

The next step is to use the tabs at the top of the page to select which types of data you would like to use to filter your {{group}}.  Explanations of the filters each tab contains are given below.  Once you have finished choosing filters, your {{group}} will include {{people}} or organisations that meet **ALL** the criteria you have entered. 

* Note on numeric and date comparisons.  In {{Lamplight}} numeric and date comparisons are inclusive (for example if you specify the date as 1st January to 15th February 2018, {{Lamplight}} will include 1st January and 15th February in the date range filter).

**{{People}} or organisations tab:** Do you want a {{group}} of individuals, or organisations? What types of {{people}} do you want?
 
![{{Auto group}}s - choosing what types of {{people}} to add]({{imgpath}}103b.png)

You cannot create a {{group}} of both {{people}} and organisations. The search for the type of {{person}} (e.g. {{user}}, {{staff}},{{contact}} etc.) is an 'OR' search: it will include those that meet **any** of the criteria selected, not just those that meet all of them. At the bottom of this page there is the option to select the date profiles were added to the system. For example, 
greater than or equal to 1st January 2017 would give you a list of all those added since the beginning of 2017.

**Address:**  In this tab you can search by particular lines of the address, any individual part of it, or by postcode. When searching by postcode, you can enter multiple postcodes (or partial postcodes) separated by a semi-colon (;). Whenever you search for text, you can select how the search should be carried out: 

  * Exact match - the phrases should be identical, but it is not case sensitive (so 'hello' matches 'HeLLo')
  * Match anywhere - will match the entire string wherever it occurs (so 'stone lane' matches '15 Stone Lane', and matches '15 Brightstone Lane', but does not match '15 Stonecroft Lane')
  * Starts like - will match any strings that start with the search string

Spaces at the beginning and end of address lines are excluded from searches.

  * Ward and Borough (if you use the Ordnance Survey look-up and Geo-code): these will be populated based on the address details in the contact tab of each profile. You can select more than one ward or borough from each list. To do this, hold down the Ctrl button on your keyboard while you click on the options that you want, e.g. Chichester and Chiltern. 

**Relationship:** On this tab you can choose to filter by the relationships between {{people}}. This allows you to create {{group}}s of, say, 'key workers', 'GPs' or 'trustees'. You also have the opportunity on this tab to use relationships to another {{group}}. For example, you may have one already set up  for people who are unemployed. If you then want to create another {{group}} consisting of the  children of people who are unemployed, when making the new children's {{group}} you can go to the 'relationships' tab, choose the original 'unemployed' {{group}} from the 'Show only people that are related to members of this {{group}}' selection box, and then choose the relationship 'child'. 

**{{User}} fields, {{staff}} fields, {{funder}} fields etc:** These tabs will enable you to filter on the custom fields that you have set up in the profiles of {{user}}s, {{staff}}, and {{funder}}s respectively.  The choices here will depend on what is in your individual system, but may include such things as demographic information.  They may not be visible at all if {{Lamplight}} has no custom fields set up.

These tabs may contain a variety of different types of field. 
* Date and number fields may be matched as either: 

  * greater than or equal to, meaning that people with a value greater (or later) than or equal to the value you specify will be included;
  * less than or equal to, meaning that people with a value less (or earlier) than or equal to the value you specify will be included;
  * equal to, meaning that only those that match this number or date will be included.

* Where there are **multi-select** options, only those that **match all** of your selections will be included in the {{group}}.

**{{Work}}**: The fields in this tab allow you to filter for {{people}} based on {{work}} records. If you want to find {{people}} that have attended based on dates, you first need to set the dates, then you need to specify the {{work}} area(s) you want to filter on. You can also choose to find {{people}} that have not attended at certain periods. So, for example:

To identify people attending at least one session of Cookery after 1st April 2012 and before 31st March 2013:

![Automatic {{groups}} - {{work}} records tab example 1]({{imgpath}}103c.png)

To identify people attending an Initial Assessment between 1st April 2012 and 30th September 2012 (equivalent to people attending between Start of Q1 2012 and End of Q2 2012)

![Automatic ((groups)) - {{work}} records tab example 2]({{imgpath}}103d.png)

To identify new users - people attending the centre after 1st April 2013 that had never attended before then:

![Automatic {{groups}} - {{work}} records tab example 3]({{imgpath}}103e.png)

To identify attendees who have completed the course - service users who in Q3 2013 attended at least 6 sessions of the 10 session Gardening course

![Automatic {{groups}} - {{work}} records tab example 4]({{imgpath}}103f.png)

Finally, you can filter by {{workarea}}, attendance type and role, and any custom {{work}} fields you have added to your system.

The **{{Outcome}}** fields tab is where you can search for {{people}} based on their outcome scores for a particular measure. You can look for {{people}} with a particular score, those who have changed over time or those who have maintained a score for a specified period of time. This will let you set up {{group}}s like '{{people}} who have gained a job and have sustained it for 6 months'. Bear in mind here that {{Lamplight}} treats yes-no {{outcome}}s as 1 - 0 (ie a 'yes' is stored as 1, and a 'no' as a 0), so to find {{people}} that have answered 'yes' to a particular {{outcome}} you'll need to enter the 'Outcome score' as 'Equal to' '1'. 

The fields in the **{{Referral}}** and **{{Grant}}** tabs work like those in the {{work}} tab, allowing you to search for {{people}} involved in a {{referral}} or {{grant}} record respectively. 

**{{Cases}}**:  This tab allows you to create a list of {{people}} who are involved in a particular case by case name, category or within a given timeframe.

When you have added all criteria, click the 'save' button in the bottom-right.


[View the video](/help/video/id/18)
###### core module

