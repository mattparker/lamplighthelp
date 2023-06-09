# 16.10.1 <i class="fa fa-chart-line"></i> Create {{Activity}} Templates

> Create {{Activity}} Templates pre-fill fields in {{activity}} records to speed up data entry.

System administrators can create {{activity}} templates that partially complete {{work}}, {{referral}}, {{outcome}},
{{grant}} and {{comm}} records. These templates are then available whereever you can create a new record. Templates
speed up data entry and increase consistency and accuracy. You'll need the {{comm}}s module to create and use those
templates.

To create, edit or delete templates, go to admin > system administration and click 'Manage create activity templates' in the 
Templates section.

![List of templates](16.10.1a.png)

Scroll down to the type of record you wish to create a template for, and click 'add' or 'edit' to change an existing one.

The Name and description will be visible to operators, and templates are listed in alphabetical order in menus, so you may wish
to give some thought to naming conventions so that templates appear in a logical order for operators. Then click on to 
the next tab.

Dates are set to be variable dates - usually you will want to choose 'yesterday', 'today' or 'tomorrow' most likely,
but there may be circumstances in which you need to use other types. If you use a template from the diary, the date
and time will be whatever was selected on the diary, not what's selected here.

![Setting the date and time of the record](16.10.1b.png)

If you leave the time blank, it will default to the current time. If you leave the duration blank, it will default to the
default duration set in global settings.

Select {{workarea}}s and locations as required, and any custom fields you have set.

Attendances can also be set here if required. This may be useful for standardised {{referral}} processes, for example.
The usual rules for attendances will still be followed: if you create a record in a profile, that person will still be
added to the attendance.

Fields in other tabs can also be completed as needed, including custom tabs and fields, and module specific tabs. You can
only attach files to {{comm}} records, however, so as to send standard attachments to people by email.

{{Message}}s use a variable date that's a bit more flexible. You can see the default {{message}} date is set as "+1 day".

![Creating template {{message}}s](16.10.1c.png)

This can be changed to other variable descriptions, for example:

- yesterday
- today
- tomorrow
- +10 days
- -1 week
- +3 months
- +1 year
- next Wednesday

When you come to use a template, Lamplight will first calculate the overall date of the record from the setting in the 
'When and where' tab set earlier. It will then set the dates of {{message}}s relative to that date.

For example, let's say you set the overall record date to be 'tomorrow' in the 'When and where' section of the template.
You create a {{message}} with a date of '+2 weeks'.

Someone uses the template on the 28th June 2023. The 'date from' and 'date to' of the record will be 29th June 2023, and
the date of the {{message}} will be two weeks on from that - the 13th July 2023.

These dates are set when you initially request the template record - so if the operator changes the 'date from' of the
record they are creating, the {{message}} dates won't update automatically (it'd get quite confusing if they did).

Click save when you are happy with your template.

Once it's saved, to see it appear on the main menu you'll need to reload Lamplight (press f5) and you'll see the template
appear on the main menu:

![Creating template {{message}}s](16.10.1d.png)

You'll also see templates in the relevant profile tabs, the {{linked case}} tab, and {{comm}}s templates appear on the
context menu, as a submenu to {{Comm}}. See [7.1.7 Creating {{work}} records from templates](/help/index/p/7.1.7) and
[21.3.2 Using {{comm}}s templates](/help/index/p/21.3.2) for more on these.


<iframe width="640" height="564" src="https://player.vimeo.com/video/834103658" frameborder="0" allowFullScreen mozallowfullscreen webkitAllowFullScreen></iframe>



##### Tags
Time saving tips
System admin

###### core module

