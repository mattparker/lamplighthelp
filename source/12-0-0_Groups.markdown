# 12.0.0 <i class="fa fa-users"></i> {{Group}}s

> {{Group}}s in {{Lamplight}} are collections of {{people}} or {{org}}s. You can bring together a list of profiles in different ways: {{auto group}}s (based on criteria), {{manual group}}s (choosing specific profiles individually by name) or {{merge group}}s (combining existing {{group}}s together).



### What is a {{Group}}?

A {{group}} is a collection of {{people}} or {{org}}s. You can set up any number of {{group}}s in your system, and each {{person}} in your database can belong to any number of {{group}}s. For example, you may set up the following {{group}}s:

 - Steering group members.
 - Female {{User}}s in N1 aged over 20.
 - New {{user}}s in previous quarter.
 - All youth work staff.
 - Organisations working with children.
 
 ![{{Group}}s in {{Lamplight}}](12.0.0c.png)
 
They are shared across database operators, so that if you set up a {{group}} another database operator with access to your system will be able to use it too.

### Types of {{Group}}

There are three types of {{group}}: {{manual group}}s, {{auto group}}s, and {{merge group}}s. 
- {{Manual group}}s are created by selecting the individual {{people}} or {{org}}s that you want to include. Similar to a written list of names, the {{group}} won't change unless someone manually updates the list, this can mean a pressure on data entry to ensure it's kept up to date and accurate and therefore useful/relevant.
- {{Auto group}}s are like saved searches: you enter the criteria (e.g. 'postcode starts with N1') and {{Lamplight}} searches for everyone that meets that criteria. Each time you use the {{group}}, {{Lamplight}} will automatically check again. For example, if someone moves out of the area and you update their postcode, that person will not appear in the {{group}} when it is next run. {{Auto group}}s are therefore extremely helpful when you know 'what' you want, but don't necessarily know all the profiles in the system. {{Auto group}}s can be created based on a single data set (as mentioned) or a combination of data, such as contact details, custom tab information and record data. This means it is possible to run very detailed and specific analysis, for example, {{user}}s living in a specific borough, within a age range, who have attended sessions in the last 3 months and have seen improved scores in their {{outcome}} measures. {{Auto group}}s depend on full and complete data entry for the fields used as criteria.
- {{Merge group}}s are created by joining existing {{group}}s together. {{Lamplight}} will combine all the members of each {{group}} into one, whilst allowing you to choose how they should be combined. For example, you might have a {{group}} of under 18 year olds and a {{group}} of over 65 year olds and you require a single {{group}} of 'concessions'. Alternatively you might have a {{group}} of {{user}}s who have attended group sessions and a {{group}} of {{user}}s who have received 1:1 support and you need to find out who is accessing both. As {{merge group}}s rely on existing {{group}}s (either auto or manual), operators will need to be careful not to delete {{group}}s being used for these purposes.

### Using {{Group}}s

You can use {{group}}s in different ways:

- Bulk data entry. If you have a regular {{group}} of {{user}}s that comes to a particular session every week, instead of adding them individually each time you can create a {{group}}. All you need to do then is type the name of the {{group}} into the search box on the 'Attendance' tab of your {{work}} record. {{Lamplight}} will automatically add everyone that's in the {{group}} to the attendance table in the {{work}} record (see section [7.1.2 Adding Attendance Details](/help/index//p/7.1.2)).
- {{Report}} filters. {{Group}}s can be used to filter whose data is included in a {{report}} (see section [14.1.1 {{Report}} filters](/help/index/p/14.1.1)). This will provide a report on a specific set of people. 
- {{Group}} data views. You can use data views to show detailed information about members of the {{group}} (see section [13 {{Group}} Data Views](/help/index/p/13)).
- Mailing lists. {{Group}}s can be used with {{comm}}s records to add more than one profile in one go, more efficient therefore if you need to create mailing labels for 50 people for example. If you use MailChimp with Lamplight, you can sync {{group}}s from Lamplight directly into MailChimp (see section [21.2 Communications Module: Linking with MailChimp Overview](/help/index/p/21.2)).


##### Tags
Experienced user
{{Group}}

###### core module

