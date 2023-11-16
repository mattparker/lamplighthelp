# 21.1.4 List of All Word Template Merge Tags

> Merge tags in Word Templates are replaced with information from profiles and {{activity}} records. This is the list of all the tags you can use.

These are the mail merge tags you can use in [Word templates](/help/index/p/21.1.3). They are all case-senstive and need to be entered into your templates exactly as they appear here. Some of these fields might have been translated (or renamed) in your system, but you will need to use the original names (e.g. if you have 'House number' instead of 'Address line 1' on the contact details tab of a profile, you need to use 'Address line 1' in your templates). You can see which terms have been changed in your system by going to Admin > System administration > Customise {{Lamplight}} > Change terms used in Lamplight For en_GB'.

### Profile Tags - Name and Contact Details

| Field | Tag |
| :--- | :--- |
| Title | ${Title} |
| First name | ${First name} |
| First name initial | ${First name initial} |
| Middle name | ${Middle name} |
| Middle name initial | ${Middle name initial} |
| Surname | ${Surname} |
| Surname initial | ${Surname initial} |
| Suffix | ${Suffix} |
| Organisation name | ${Organisation name} |
| Organisation name if available | ${Organisation name if available} |
| Address line 1 | ${Address line 1} |
| Address line 2 | ${Address line 2} |
| Address line 3 | ${Address line 3} |
| Address line 4 | ${Address line 4} |
| Address line 5 | ${Address line 5} |
| Postcode | ${Postcode} |
| Phone | ${Phone} |
| Mobile | ${Mobile} |
| Email | ${Email} |
| Web | ${Web} |
| ID | ${bodyid} |


### Linked (Related) Profile Tags

You can use the tags above to add information from a linked profile (where two profiles appear in one line of the recipients table) by inserting the word 'Linked' into the tag name.

| Field from linked profile | Tag |
| :--- | :--- |
| Title | ${Linked Title} |
| First name | ${Linked First name} |
| First name initial | ${Linked First name initial} |
| Middle name | ${Linked Middle name} |
| Middle name initial | ${Linked Middle name initial} |
| Surname | ${Linked Surname} |
| Surname initial | ${Linked Surname initial} |
| Suffix | ${Linked Suffix} |
| Organisation name | ${Linked Organisation name} |
| Organisation name if available | ${Linked Organisation name if available} |
| Address line 1 | ${Linked Address line 1} |
| Address line 2 | ${Linked Address line 2} |
| Address line 3 | ${Linked Address line 3} |
| Address line 4 | ${Linked Address line 4} |
| Address line 5 | ${Linked Address line 5} |
| Postcode | ${Linked Postcode} |
| Phone | ${Linked Phone} |
| Mobile | ${Linked Mobile} |
| Email | ${Linked Email} |
| Web | ${Linked Web} |


### Operator Profile Tags

You can use the tags below to add information from the profile of the operator creating the {{comm}}:

| Field from profile | Tag |
| :--- | :--- |
| Title | ${me\|Title} |
| First name | ${me\|First name} |
| First name initial | ${me\|First name initial} |
| Middle name | ${me\|Middle name} |
| Middle name initial | ${me\|Middle name initial} |
| Surname | ${me\|Surname} |
| Surname initial | ${me\|Surname initial} |
| Suffix | ${me\|Suffix} |
| Organisation name | ${me\|Organisation name} |
| Organisation name if available | ${me\|Organisation name if available} |
| Address line 1 | ${me\|Address line 1} |
| Address line 2 | ${me\|Address line 2} |
| Address line 3 | ${me\|Address line 3} |
| Address line 4 | ${me\|Address line 4} |
| Address line 5 | ${me\|Address line 5} |
| Postcode | ${me\|Postcode} |
| Phone | ${me\|Phone} |
| Mobile | ${me\|Mobile} |
| Email | ${me\|Email} |
| Web | ${me\|Web} |



### Special Tags

${today} will insert today's date in the format '1st March 2020'.

${repeat_template} (your content here) ${/repeat_template} will create a copy of (your content here) for each recipient, with any merge fields completed. If you want to start a new letter or document for each recipient, put a page break after (your content here), and the '${/repeat_template}' at the top of the new page. 

${repeat_row} at the start of a table row will repeat that row for each recipient of the {{comm}}, with merge tags in the rest of the row merged from the profile.


### Custom Profile Fields

Data from the custom profile fields of recipients can be inserted by typing the field name in the merge tag. So the tag for the field 'Gender' in your system would be ${Gender}.

The spelling and capitalisation has to be exactly as it appears in your system. If you have any difficulties with this we recommend that you [download your system settings](https://lamplight.online/en/admin/uploadfields/type/get_settings) into a spreadsheet that you can copy and paste from.  

Please note: all the fields in your system need to have a unique name. If you have two with the same name (even if they are in separate profile tabs) you will get unpredictable results, as {{Lamplight}} will not know which one you’re referring to.  

Custom field names with $, { or } in them may also result in unpredictable results as this will confuse the formatting in your template, so should be avoided for this reason. 


### {{Work}} Record Tags

These can be used in [templates used from a specific {{work}} record](/help/index/p/21.3.1).

| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| Summary | ${description} | (just the text that appears in the record) |
| Description | ${description} | (just the text that appears in the record) |
| Follow up | ${followup} | (just the text that appears in the record) |


### {{Referral}} Record Tags

These can be used for templates which will be used in conjunction with a {{referral}} record - this is the same principal as for {{work}} records, above.

| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| {{Referral}} reason | ${referral reason} | (just the text that appears in the record) |
| {{Referral}} notes | ${referral notes} | (just the text that appears in the record) |
| Appointment date | ${appointment date} | 14/04/2020 |

### {{Grant}} Record Tags

These can be used for templates which will be used in conjunction with a {{grant}} record - this is the same principal as for {{work}} records, above.


| Field | Tag | Example |
| :--- | :--- | :--- |
| Date from | ${date from} | 12/04/2020 |
| Date to | ${date to} | 13/04/2020 |
| Day of date from | ${day from} | Monday |
| Start time | ${start time} | 10:30 |
| End time | ${end time} | 13:15 |
| Workarea | ${workarea} | Advice services |
| ID | ${record id} | 4812 |
| Summary | ${description} | (just the text that appears in the record) |
| Description | ${description} | (just the text that appears in the record) |
| Monitoring | ${monitoring} | (just the text that appears in the record) |
| Amount | ${amount} | 150 |
| {{Grant}} type | ${grant type} | Capital |
| Approval date | ${approval date} | 18/04/2020 |


###### comms module
