# 16.6.3  <i class="fa fa-cogs"></i> System Administration: Relationships

> Relationships are a way of linking profiles to show their connections to one another. For example, they could link a person to an organisation, or a parent to a child



Relationship types are added, edited and deleted in the same way as other drop-down list items previously described - see [16.6.0 System Administration: Lists](/help/index/p/16.6.0).

To add a new one, or edit an old one: 
- Go to 'admin -> system administration -> Manage Custom Fields and Drop-down Lists -> People and Organisations -> Relation types between people'.

### Inverse Text
Some relationships have two different sides, depending on whose profile you are looking from. If you are my **friend**, then (hopefully) I am also your **friend**. However, if you are my **parent** then I am not your **parent**, I am your **child**. 'Inverse text' allows you to set up the two differend sides for the relationship.

- Add the initial relationship (e.g. "parent") in the 'Text' box.
- In the 'Inverse text' box, add the other side of the relationship (in this case "child"). 

![Inverse Text](16.6.3a.png)

### Linked Records
There is also a checkbox for 'Use in linked records'. If you decide to do this then {{people}} or {{org}}s who have this type of relationship can be added to the attendance table of an {{activity}} record together.

- When you use the search box in the 'Attendance' tab of a record, the name of the {{person}} or {{org}} you are searching for will appear there.
- If they have any relationships of this type, there will be another item in the search results list with the name of the {{person}} or {{org}} with whom they have this relationship appearing next to them. 

![Linked Relationships in a {{Work}} Record](16.6.3b.png)

- If you choose the linked option (rather than the {{person}}'s name by itself), the record will be attached to both profiles and you will be able to report on the attendance of both of them.  It will count as one attendance in reporting, rather than the two attendances that would show if you added them separately.

One example of when this is useful is if you are running training and people attending are there on behalf of an organisation.  You need to know both the name of the person and their organisation, and they need to be shown together so you know which person is from which organisation.  It's only actually one attendance at the training session, so you need to use linked relationships to record their attendance.

- Once you have finished the relationship details, click 'Update'. 
- Remember to click 'save all changes' at the top or bottom of the page before you leave. If you navigate away from this page before saving then your changes will be lost.

###### core module

