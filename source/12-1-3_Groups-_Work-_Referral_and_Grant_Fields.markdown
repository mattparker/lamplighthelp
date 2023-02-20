# 12.1.3  <i class="fa fa-users"></i> {{Auto group}}s: {{Work}}, {{Referral}} and {{Grant}} Fields

> You can use the information stored in your {{activity}} record fields to search for {{people}} or {{org}}s who have taken part in particular activities, or who have donated in a specific timeframe. For example, {{user}}s who have attended {{work}} sessions in the last 6 months, or {{funder}}s who have donated over a certain amount in the last year

Each record type within the {{auto group}} setting asks you to firstly select a timeframe (a date range of interest), which in turn creates three periods of time.
- time BEFORE the date range
- time DURING the date range
- time AFTER the date range

With this flexibility you can answer many questions with the same template settings. So you can identify {{list}}s such as:
- those who have attended
- new {{people}}
- those who haven't attended as least 3 times
- who were attending, but have since stopped.

Below we explain some examples of these.

### {{Work}} Fields

The fields in this tab allow you to filter for {{people}} or {{org}}s based on the {{work}} records in their profile. 
If you want to find {{people}} that have attended sessions based on dates:
- you first need to set the dates,
  - please note that the dates chosen can either be 'fixed' or you can utilise the 'dynamic' date options, such as 'current month'. If you use these date types, when you re-run the list, {{Lamplight}} will know what the present day is and will therefore calculate what the 'current month' is.
- then you need to specify the {{workarea}}(s) you want to filter on (ie. which sessions)
- and select their attendance role/type

You can also choose to find {{people}} that have not attended at certain periods or have been involved in specific records based on any custom tabs you have in your system.

#### To identify {{user}}s attending at least one session of Life Skills after 1st April 2018 and before 31st March 2019

- For the Date range of interest select between 'Fixed date' from the drop-down and select 1st April 2018 as then choose 'Fixed date' from the drop-down menu, then select 1st April 2019 as the value. {{Lamplight}} will **not include** records occuring on the last day of date frame, so if you want records to 31st March, you have to enter the following day, ie 1st April.
- Next go to the 'Number of records in profile **within** the date range' (the middle line from the next set of three). You are looking for people with at least one record between those dates, so choose 'At least' on the drop-down, then type '1' in the text box after it.
- You want people who went to the sessions, so from the 'Attendance type' drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
- In the drop-down box for 'Role', select '{{User}}'. This will exclude other attendees, such as {{staff}} or {{volunteer}}s.
- Finally, under {{workarea}}, choose 'Life Skills'.

If you have added all the other filters that you need, and filled in the name and description on the first tab ('{{Group}} name'), scroll to the bottom of the page and click 'Save'.

![Automatic {{group}}s - {{work}} records tab example 1](12.1.3a.png)


#### To identify NEW {{user}}s - people attending after 1st April 2019 that had never attended before then

Depending on your workflow, you can also use {{group}}s to show people you first worked with in a specific timeframe. This {{group}} includes {{people}} or {{org}}s who have a {{work}} record in the span of time that you're looking at, but do not have any {{work}} records before that point.

- For the Date range of interest select your preferred timeframe, our example is Q2 2022 (please note, {{Lamplight}} Quarters start on 1st April, therefore the start of Quarter 2 is 1st July). {{Lamplight}} will **not include** records occuring on the last day of date frame, so if you want to include the whole of Q2, you have to enter the following day, ie the start of Q3.
- You want to find {{people}} who have a record between those dates, so go to the 'Number of records in profile **within** the date range' (the middle line from the next set of three), choose 'At least' on the drop-down, then type '1' in the text box after it.
- To narrow it down to people who did not attend any {{work}} sessions before that date, go to the line above 'Number of records in profile before (but not including) the first day of the date range'. From the drop-down box, choose 'Exactly', and in the next box enter '0'. This will now only show people who did not have any {{work}} records before your start date, but have attended at least once during.
- Underneath that, in the 'Attendance' drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
- In the drop-down box for 'Role', select '{{User}}'. This will filter out other attendees, such as {{staff}} or {{volunteer}}s.
- If you want to, you can also select {{workarea}}s and {{subworkarea}}s to narrow down your search further. If you select multiple {{workarea}}s or {{subworkarea}}s, then {{Lamplight}} will include profiles of {{people}} who have been involved in any of them - they do not need to have a record for each of the areas chosen.

![Auto {{group}}s - {{work}} records tab example 3](12.1.3b.png)


#### To identify attendees who have completed the course - {{user}}s who in the current school year attended at least 6 sessions of the 10 session Gardening course

This example assumes that to have officially completed the Gardening course participants would need to attend at least 6 of the 10 sessions.

- For the Date range of interest select your preferred timeframe, our example is the current school year, so we've selected the start and the end. {{Lamplight}} takes the school year as starting on 1st September each year and ends on 31st August. {{Lamplight}} will **not include** records occuring on the last day of date frame, so if you know no sessions took place on 31st August, you can use 'End of current school year' and {{Lamplight}} will only include those occurring on 30th August.
- You want to find {{people}} with records between those dates, so next go to the 'Number of records in profile **within** the date range' (the middle box from the next set of three). You are looking for people with a minimum of 6 and a maximum of 10 records between those dates, so choose 'Between' from the drop-down, then type '6' in the next box, and '10' in the second one.
- Next you need to specify that these are {{people}} who attended, so from the 'Attendance type' drop-down box choose 'Attended'. This will exclude anyone who was not actually at the session.
- In the drop-down box for 'Role', select '{{User}}'. This will exclude other attendees, such as {{staff}} or {{volunteer}}s.
- Finally, this is a {{subworkarea}}, so first select the {{workarea}} 'Learning Curve', then the {{subworkarea}} 'Gardening' so that your results do not include all attendees of other {{workarea}}s.

![Automatic {{group}}s - {{work}} records tab example 4](12.1.3c.png)


### {{Referral}} and {{Grant}} Fields

The fields in the **{{Referral}}** and **{{Grant}}** tabs function like those in the {{work}} tab, allowing you to search for {{people}} involved in a {{referral}} or {{grant}} record respectively. You can filter by the dates of records in the profile, as well as using {{workarea}}s and custom fields from your {{referral}}s and {{grant}}s.


###### core module

