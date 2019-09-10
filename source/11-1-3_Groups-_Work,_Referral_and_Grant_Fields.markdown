# 11.1.3 {{Group}}s: {{Work}}, {{Referral}} and {{Grant}} Fields

> You can use the information stored in your {{activity}} record fields to search for {{people}} or {{org}}s who taken part in particular activities, or who have donated in a specific timeframe. For example, you could filter for {{user}}s who have attended {{work}} sessions in the last 6 months, or {{funder}}s who have donated over a certain amount in the last year

### {{Work}} Fields

The fields in this tab allow you to filter for {{people}} or {{org}}s based on the {{work}} records in their profile. If you want to find {{people}} that have attended sessions based on dates, you first need to set the dates, then you need to specify the {{work}} area(s) you want to filter on. You can also choose to find {{people}} that have not attended at certain periods. So, for example:

**To identify {{user}}s attending at least one session of Life Skills after 1st April 2018 and before 31st March 2019:**

- For Date 1 (this will be your 'from' date), choose 'Fixed date' from the drop-down and select 1st April 2018 as the 'value'. {{Lamplight}} will **include** the date that you choose in the search filter.
- For Date 2 (your 'to' date) choose 'Fixed date' from the drop-down menu, then select 1st April 2019 as the 'value'. {{Lamplight}} will **not include** 'Date 2' in the search filter, so if you want records to 31st March, you have to enter the following day, 1st April.
- Next go to the 'Number of records in profile **between** date 1 and 2' (the middle line from the next set of three). You are looking for people with at least one record between those dates, so choose 'At least' on the drop-down, then type '1' in the text box after it.
- You want people who went to the sessions, so from the 'Attendance type' drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
- In the drop-down box for 'Role', select '{{User}}'. This will exclude other attendees, such as {{staff}} or {{volunteer}}s.
- Finally, under {{workarea}}, choose 'Life Skills'.

![Automatic {{group}}s - {{work}} records tab example 1](11.1.0b.png)

If you have added all the other filters that you need, and filled in the name and description on the first tab ('{{Group}} name'), scroll to the bottom of the page and click 'Save'.

**To identify {{staff}} attending a Housing session between 1st April 2019 and 30th September 2019 (equivalent to people attending between Start of Q1 2019 and End of Q2 2019)**

- For Date 1 (this will be your 'from' date), choose 'Start Quarter 1' from the drop-down, then select '2019' from the box below that.
- For Date 2 (your 'to' date) 'End Quarter 2' from the drop-down, then '2019' from the box below that.
- You want to find records between those dates, so next go to the 'Number of records in profile **between** date 1 and 2' (the middle box from the next set of three). You are looking for people with at least one record in their profile between those dates, so choose 'At least' on the drop-down, then type '1' in the text box after it.
- Underneath that, you want people who attended, so from the 'Attendance' drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
- In the drop-down box for 'Role', select '{{Staff}}'. This will filter out other attendees, such as {{user}}s or {{volunteer}}s.
- Finally, 'Housing' is a {{subworkarea}}, so first choose 'Life Skills' under {{workarea}}, then 'Housing'.

![Automatic ((group))s - {{work}} records tab example 2](11.1.0c.png)

If you have added all the other filters that you need, and filled in the name and description on the first tab ('{{Group}} name'), scroll to the bottom of the page and click 'Save'.

**To identify new users - people attending the centre after 1st April 2019 that had never attended before then:**

Depending on your workflow, you can also use {{group}}s to show people you first worked with in a specific timeframe. This {{group}} includes {{people}} or {{org}}s who have a {{work}} record in the span of time that you're looking at, but do not have any {{work}} records before that point.

- For Date 1 (this will be your 'from' date), choose 'Fixed date' from the drop-down and select to 1st April 2019. {{Lamplight}} will  **include** this date in the search filter.
- For Date 2 (your 'to' date) choose 'Today'. That will filter up to the current day, whenever you run the {{group}}.
- You want to find {{people}} who have a record between those dates, so go to the 'Number of records in profile **between** date 1 and 2' (the middle line from the next set of three), choose 'At least' on the drop-down, then type '1' in the text box after it.
- To narrow it down to people who did not attend any {{work}} sessions before that date, go to the line above 'Number of records in profile prior to (but not including) date 1'. From the drop-down box, choose 'Exactly', and in the next box enter '0'. This will now only show people who did not have any {{work}} records before your start date.
- Underneath that, in the 'Attendance' drop-down box choose 'Attended'. This will exclude people who are shown in the attendance table as 'Booked', or 'For reference', for example.
- In the drop-down box for 'Role', select '{{User}}'. This will filter out other attendees, such as {{staff}} or {{volunteer}}s.
- If you want to, you can also select {{workarea}}s and {{subworkarea}}s to narrow down your search further. If you select multiple {{workarea}}s or {{subworkarea}}s, then {{Lamplight}} will include profiles of {{people}} who have been involved in any of them - they do not need to have a record for each of the areas chosen.

![Auto {{group}}s - {{work}} records tab example 3](11.1.0d.png)

**To identify attendees who have completed the course - service users who in Q3 2019 attended at least 6 sessions of the 10 session Gardening course**

This example assumes that to have officially completed the Gardening course participants would need to attend at least 6 of the 10 sessions.

- For Date 1 (this will be your 'from' date), choose 'Start Quarter 3' from the drop-down, then select '2019' from the box below that.
- For Date 2 (your 'to' date), select 'End Quarter 3' from the drop-down, then '2019' from the box below that.
- You want to find {{people}} with records between those dates, so next go to the 'Number of records in profile **between** date 1 and 2' (the middle box from the next set of three). You are looking for people with a minimum of 6 and a maximum of 10 records between those dates, so choose 'Between' from the drop-down, then type '6' in the next box, and '10' in the second one.
- Next you need to specify that these are {{people}} who attended, so from the 'Attendance type' drop-down box choose 'Attended'. This will exclude anyone who was not actually at the session.
- In the drop-down box for 'Role', select '{{User}}'. This will exclude other attendees, such as {{staff}} or {{volunteer}}s.
- Finally, this is a {{subworkarea}}, so first select the {{workarea}} 'Learning Curve', then the {{subworkarea}} 'Gardening' so that your results do not include all attendees of other {{workarea}}s.

![Automatic {{group}}s - {{work}} records tab example 4](11.1.0e.png)


### {{Referral}} and {{Grant}} Fields

The fields in the **{{Referral}}** and **{{Grant}}** tabs function like those in the {{work}} tab, allowing you to search for {{people}} involved in a {{referral}} or {{grant}} record respectively. You can filter by the dates of records in the profile, as well as using {{workarea}}s and custom fields from your {{referral}}s and {{grant}}s.


###### core module

