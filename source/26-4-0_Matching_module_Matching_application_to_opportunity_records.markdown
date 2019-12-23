# 26.4.0 Matching Module - Matching {{Volunteering Application}} and {{Volunteering Opportunity}} Records

> {{Lamplight}} will use the details saved in {{volunteering opportunity}} and {{volunteering application}} records to automatically find the best matches

{{Volunteering application}} and {{volunteering opportunity}} records each have a location, times (availability), and some categories to define what they involve. These details can be used to find appropriate matches of {{volunteer}}s to roles.

You can search for {{volunteering application}}s which match {{volunteering opportunity}} records and vice versa. {{Lamplight}} will calculate an overall score and use these to list the best matches in order.

### How to Match

- Find the record that you want to find matches for.  You can either find these in the profiles of those involved, or from the main menu: {{activity}} > view > {{volunteering opportunity}} (or {{volunteering application}}). For this example we're looking at {{volunteering opportunity}} records and finding {{volunteering application}} records which match them, but you can also start with a {{volunteering application}} and find {{volunteering opportunity}} records to match in just the same way.  

- [Use the search filters](/help/index/p/26.3.0) to find the record you need, then right-click (or click the menu button in the left-hand column of the table) to bring up the context menu:

![{{Volunteering opportunity}} context menu](26.3.0c.PNG)

#### Match on All Criteria

If you select this, {{Lamplight}} will search for records that are near to the address, have some crossover in availability, and have most interests in common.

#### Match Nearby

If you choose this option you will be shown records in order of distance, ignoring other factors.  Distance is calculated as the crow flies, using the latitude and longitude of the postcodes of in the 'Contact details' tab of profiles for the {{people}} who have made a {{volunteering application}} and those providing the {{volunteering opportunity}}.

#### Match by Interests

This option shows records ranked by how many interests the {{volunteering application}}s have in common with the {{volunteering opportunity}}.

Interests are the checkboxes you tick when entering a {{volunteering application}} or {{volunteering opportunity}}. They will be labelled something like 'interests', 'topics', 'requirements', 'ideal for', and 'skills gained' (although as they are customisable they  may be called something different in your system).

#### Match Availability

When you choose this option, {{Lamplight}} will only look for records that have some availability overlap. If start and end dates are specified they will be used, as well as whether the {{volunteer}} is free on the days and times specified in the {{volunteering opportunity}}.  Records with more common time slots will be shown higher in the list.


### Using the Matched Records

Running a match (using any of the options above) will return a summary of the {{volunteering opportunity}} that you are seeking matches for, with a summary of each possible matching {{volunteering application}} below it:

![Showing matches](26.4.0a.PNG)

Use the scrollbar in the bottom half of the window to scroll down through the matching records: the best matches are shown at the top.  If you wish to match a {{volunteering application}} to the {{volunteering opportunity}}, click the 'Add to the opportunity' button on the {{volunteering application}} in question. The {{volunteering applicant}} will then be added to the {{volunteering opportunity}} attendance table, and the {{volunteering opportunity}} will show in the {{volunteer}}'s profile tab.


###### match module
