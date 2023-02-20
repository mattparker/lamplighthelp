# 12.1.1 <i class="fa fa-users"></i> {{Auto group}}s: Address and Relationship Fields

> Use the 'Address' and 'Relationships' tabs to filter the members of your {{auto group}} based on their locality or links to other {{people}} on the system



### Address

In this tab you can choose to filter by particular lines of the address, any individual part of it, or by postcode. 

![Address Tab in {{Group}}s](11.1.1a.png)

- When searching by postcode, you can enter multiple postcodes (or partial postcodes) separated by a semi-colon (;).  So if you want people living in AB10 or AB11 postcode areas, enter 'AB10;AB11' and select 'Starts like' in the drop-down.
- If you want everyone living in a particular town, say, but aren't sure which address line the town is entered into, you can use 'OR search any line of address' and that will look in all of them for your search term.

Whenever you search for text, you can select how the search should be carried out: 

![Search Options for Addresses in {{Group}}s](11.1.1b.png)

  - Exact match: the phrases must be identical, but it is not case sensitive (so 'hello' matches 'HeLLo').
  - Match anywhere: will match the entire string wherever it occurs (so 'stone lane' matches '15 Stone Lane', and matches '15 Brightstone Lane', but does not match '15 Stonecroft Lane').
  - Starts like: will match any strings that start with the search string (so 'Brighton' will match 'Brighton Villas' but not 'New Brighton').
  - Is empty: finds all profiles that do not have any information in the field (for example postcode).
  
Also note that:
- Spaces at the beginning and end of address lines are excluded from searches.
- Ward and Borough (if you use the Ordnance Survey look-up and Geo-code): will be populated based on the address details in the contact tab of each profile. You can select more than one ward or borough from each list. To do this, hold down the Ctrl button on your keyboard while you click on the options that you want, e.g. Chichester and Chiltern. To deselect an option, Ctrl click again.

### Relationships

On this tab you can choose to filter by the relationships that are recorded in the profile.  You can create {{auto group}}s of, for example, all the {{people}} who have a relationship of 'key worker', 'GP' or 'trustee' (if these are relationships that you use in your system - you will probably have different options to choose from). 
If you wish to select more than one relationship type, use the Ctrl button on your keyboard to select multiple options.

![Relationships Link in {{Group}}s](12.1.1a.png)

The date frame that shows below the relationship list, allows you to specify when the system should use the relationship. If you leave it blank, it will include relationships that are current as at the time the {{group}} is run. You can however specify a time frame from the drop-down lists. 

If you use default contacts in your system (ie. specify who the default contact is when creating a relationship in a profile) it is also possible to select this as a filter in the 'Relationships' tab, so that only default contacts are included.

The option 'Include related profiles as the second profile for each {{group}} member' controls whether the related profiles should appear as the 'second' profiles when viewing and using the {{group}}.  For example, these can be used in {{comm}}s, so that you can include details of both profiles in a single merged {{comm}}.  But you may also want to exclude this possibility.  Tick the box if you do want the linked profiles to appear.

You can also use relationships to only show profiles that are related to members of another {{auto group}}. 
- For example (using the settings in our demo system) you may need a {{group}} of parents with children under 5. You firstly create an {{auto group}} for "Children under 5" and then come to the 'Relationships' tab to create another (a second) {{auto group}} of the parents of these children  
  - Choose the original 'Children under 5' {{group}} from the 'show only profiles that are related to members of {{group}}' drop-down.
  - Select the relationship 'Family' from the 'With relationship' box.
  
![Using 'Related to Members of {{Group}}' in {{Group}}s](12.1.1b.png)





###### core module
