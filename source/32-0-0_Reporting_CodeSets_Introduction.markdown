# 32.0.0 Reporting CodeSets Module

> Reporting CodeSets allow you to "translate" your data, so that you can output it using code sets for partners for reporting purposes.  

Reporting CodeSets are like an automated find-and-replace that act on your data.  Our customer webinar
video gives a broad introduction to Report Codesets, explaining what they are, how they work, and how to use them.
It's the best place to start.

<iframe title="Report CodeSets webinar" width="640" height="564" src="https://player.vimeo.com/video/757121112?h=a3e5ac0cab&badge=0&autopause=0&player_id=0&app_id=58479"
data-video-display="home" frameborder="0" allowFullScreen mozallowfullscreen webkitAllowFullScreen></iframe>

The next easiest way to explain what they do is with an example:

### Example scenario: the problem

In your system you have a drop-down 'Gender' field in your profiles with various options.  You are required to 
provide a list of service users and their gender by a commissioner.  However, instead of words like 'Female', 'Male', 
and 'Non-binary', the commissioner requires you to submit coded data, where '01' means 'Female', '02' means 'Male', and
'03' means non-binary.

### Example scenario: possible solutions

You could change the labels of your gender options in your system. But that would mean remembering which is which - 
and is not easy to use day-to-day.

Or you can download a {{group}} and data view to Excel and then do a lot of find-and-replace.  This is very time 
consuming and prone to error.  And if you've tried, you'll know that Excel helpfully does things like change '01' to '1',
which is invalid when you come to submit the data.

### Example scenario: how CodeSets solve this problem

A Reporting CodeSet can be set up to do this for you.  You tell Lamplight what the codes are for each gender option, and then when you
run the {{group}} with the data view and CodeSet, the table now shows '01', '02', and '03' in the Gender column.  You 
can do this for as many fields as you like, with different rules for how the data is translated.

This functionality has been developed to help customers export data for the MHS DS (NHS Mental Health Service Data Set).
There is a large amount of data that needs to be coded in this way, and by spending the time setting up Reporting 
CodeSets and templates, it can be generated in a few minutes and be compliant with the data requirements for submission.

### Other ways they can be used.

The same functionality can be used for any purposes, though.  You can create multiple CodeSets for different reasons
and with different codings, so a single source of data (Lamplight) can be translated in many different ways.

Because of the complexity of the data typically required by MHS-DS, setting up CodeSets correctly can take some time
and expertise.  If required, Lamplight can help you to set up your CodeSets and templates for you to meet the requirements.

When setting up CodeSets there is some key terminology to understand.  A CodeSet is a collection of 'Maps'.  Each map
is for a particular field in your system (e.g. workarea, date of birth etc) and takes you from the data you have, to 
the output you need.

In our example above, a map is a bit like this:

**Field: gender**

| **From**   | =>  | **To** |
|------------|-----|--------|
| Female     | =>  | 01     |
 | Male       | => | 02     |
| Non-binary | => | 03     |
etc.

A CodeSet is a collection of these individual field maps.

As well as changing the values in the table, Maps can also change the column headers if needed.


###### codeset module
