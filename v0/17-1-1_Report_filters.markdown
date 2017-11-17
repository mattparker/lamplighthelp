# 17.1.1    {{Report}} filters

> All {{report}}s let you filter by date, {{workarea}} and {{group}}. Other filters are available depending on the {{report}}. 

All {{report}}s have the same set of filters initially, shown below:

![{{Report}} filters]({{imgpath}}1216a.png)

The date from and date to fields will show records dated between these two dates, including the dates selected.

The {{workarea}} button allows you to filter for particular {{workarea}}s, or {{subworkarea}}s.

The locations button allow you to filter by where the activity took place 

The {{group}} filter lets you use {{group}}s (see section [14.0.0  Introduction to {{group}}s](/help/index/v/{{version}}/p/14.0.0)) to restrict the {{report}} to a particular set of {{people}}. The {{report}} will show data for the members of the {{group}}, but does not apply the filters for the {{group}} to the {{report}}.

For example, you may create a {{group}} of everyone attending any piece of {{work}} in April 2011, giving you a list of {{people}}. You can now use this {{group}} as a filter to see how much {{work}} you have done with these people in June 2011. To do this, select 'date from' in your {{report}} as 1st June; date to as 30th June; and in the {{group}} drop-down select the name of your {{group}}.

{{Lamplight}} will identify everyone in the {{group}}, and then show data for records that those people have attended. So the data it shows will be the number of attendances in June, not April.

The attendance type option allows you to filter so that you can create a {{report}} just based on those who attended, rather than include those listed who did not attend or cancelled, (this will depend on the way your organisation has chosen to use the attendance type option.)

The role filter will filter based on how the person attended the activity, for example allowing you to view just {{user}}s or just {{staff}} who attended the sessions.

Profile type drop-down option allows you to filter by {{person}}, {{organisation}} or {{family}} profiles (if they have been enabled by your system administrator). 
Include information about linked profiles will information about attendees enter via default {{relationship}}s (For example, entered in the attendance table as {{Person}} 1, {{person}} 2).
You can also choose to exclude anonymous attendees from your {{report}}s.  This may be useful when reporting on particular activities, and can also be useful when troubleshooting reports, where you are seeking to understand how many of the ‘unknown’ breakdown results are from anonymous users, and how many have simply not been entered.

[View the video](/help/video/id/34)
###### core module


