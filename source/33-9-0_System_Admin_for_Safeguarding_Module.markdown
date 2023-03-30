# 33.9.0 {{Safeguarding}} Module System Admin

> There are a number of settings for the {{safeguarding}} module that you can change via system admin.

Changes to the settings for the {{safeguarding}} module can be made using familiar system admin interfaces.  They are
listed below, with any notes particular to these settings.  You will need to be a system administrator to make these changes.

### {{Safeguarding}} Managers

Any operator can be a {{Safeguarding}} Manager - it is separate to the standard operator roles. To do so,
go to admin > system administration > manage database operators and edit the operator. You will see a checkbox
to enable them as a {{Safeguarding}} Manager. As soon as you do, they will have full access to all {{Safeguarding case}}s.
They will also be able to access all DBS records.

To give someone access to DBS records only, tick the 'Give this operator access to DBS records?' box only.

### Global Settings

There is a {{safeguarding}} module tab in global settings. This allows you to change:

 - whether to include {{workarea}} and location fields on the initial {{safeguarding case}} form
 - whether to automatically assign the member of staff raising a {{safeguarding case}} to it as a {{safeguarding lead contact}}. 
 - default notification settings for new {{safeguarding case}}s
 - in multi-project systems, whether to keep {{safeguarding case}}s in separate projects or allow access across all
 - whether to display the audit log system messages in a {{safeguarding case}} when first viewing a {{safeguarding case}}. The comments can always be viewed by clicking the 'toggle messages' button.
 - the settings for the {{safeguarding}} dashboard
 - which profile roles should have DBS Checks
 - when to start notifying you when DBS checks are going to expire

Edit global settings in the [usual way](/en/help/index/p/16.12.0) via admin > system administration > change global settings.



### Attendance roles

When raising a {{safeguarding case}} additional profiles can be added to it. You may wish to create particular attendance
roles for these that relate specifically to {{safeguarding}}. You can do so via admin > system administration > Attendance roles.
Select {{safeguarding}} as the record type for the roles that you create or wish to use.


### Module specific drop-downs and custom fields

You can change the key drop-downs that appear in {{safeguarding case}}s, for Status, Severity, and Closure Reason. While
you can change the terminology, we very strongly suggest that you do not change the meaning and intention for Status
 and Severity.  These settings are found in admin > system administration > {{Safeguarding}} module box near the bottom of the screen.

Lamplight expects the Statuses that already appear in the system. If you change the meaning of the items in the Status
list, it will not behave as you expect. If you add additional items, Lamplight won't know what Actions should apply, 
and few will appear. Please only change Status items if you wish to change the terminology used, but not the meaning.

Lamplight also expects five severity values, with item ID 1 being the lowest severity. The colour coding is based on these
meanings. You could add additional items, but they will not be colour coded. We recommend you only edit for terminology,
not meaning, and do not add to the list.

Closure reasons can be edited to meet your own requirements: Lamplight does not have any built-in expectations about this list.

You can also add custom fields to:
 - {{safeguarding case}}s
 - {{safeguarding}} notes
 - {{safeguarding}} final report records
 - DBS Check records

For help in making changes to these, [please see section 16.6.0](/en/help/index/p/16.6.0) of the manual. 

There is one new option when adding custom fields to {{safeguarding case}} records. You can specify which status the field
should be used with. If you limit this, then no-one will be able to change it's value when the {{safeguarding case}} has
another status.  For example, you may want to add a custom field for the person raising the concern only: 'how did you 
come to have this concern?'. You want them to complete it when the concern is raised, but you don't want anyone to change it 
subsequently. Select 'New concern raised' in the settings for that field, and that is the only time it will be able to 
be set.


### Changing general terminology

There are several terms that appear frequently in the module that can be changed by 
[changing the terms used in Lamplight](/en/help/index/p/16.16.0). They appear in the 'other terms to translate' section.
As well as key terms, there are also placeholders that allow you provide additional help to members of staff raising
{{safeguarding case}}s.

The following terms appear on the form to create a new {{safeguarding case}}, below each field:

 - safeguarding.newconcern.casename,
 - safeguarding.newconcern.datefrom
 - safeguarding.newconcern.datedisclosed
 - safeguarding.newconcern.casedescription
 - safeguarding.newconcern.description

and on Final Report records:

 - safeguardingreport.summary
 - safeguardingreport.description

As with other types of record, you can also add custom captions and fixed text fields if you need to provide staff
with further guidance.

###### safeguarding module