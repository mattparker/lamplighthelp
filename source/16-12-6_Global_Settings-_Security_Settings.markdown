# 16.12.6 <i class="fas fa-tools"></i> Global Settings: Security Settings

> This is where System Administrators can set the amount of time before an automatic lockout happens, and restrict operators below manager level so that they can only view profiles and records of the people that they work with. It also contains the option to enable speech recognition



![Security Settings](16.12.6b.png)

### Logout Time - Length of Time in Seconds Before Automatic Logout Happens

You can set the length of time operators can leave their system open without it detecting any activity before they are
automatically logged out and need to sign in again. This is a security feature aimed at stopping systems with sensitive
data being left open at an unattended computer. Be aware that {{Lamplight}} cannot detect some activity, such as
entering text.

### Speech Recognition

#### Allow operators to use speech recognition with {{Lamplight}}?

If you use Chrome it has built-in dictation which you can use to write your {{work}} records or other text. If you
choose to enable speech recognition here, each operator will have the choice whether or not they would like to use it.

You may have privacy concerns about this (which is why it is in this section): Google will receive the audio of what you
say in order to turn it into text. You can check their privacy policy
at [https://www.google.com/chrome/privacy/whitepaper.html#speech](https://www.google.com/chrome/privacy/whitepaper.html#speech)
. If you do enable this option, when you click on a text box you’ll get a request to access your microphone: if you say
yes, you’ll be able to dictate, and after each pause the text will appear in the box. You only need to allow access once
on a particular browser, and you can revoke it at any time.

### Diary feeds

#### Allow operators create diary feeds to show read-only work records in external calender apps (e.g. Outlook)

Diary feeds are a live data export of work records in a format that can be displayed in other calendar apps, such as
Google Calendar or Outlook. This is a security setting because enabling them means that your data from Lamplight will be
accessible to the provider of your calendar app (e.g. Google or Microsoft). If you do enable these, any database
operator can create a new Diary Feed or use existing ones. The {{work}} record data that is exported includes: record
identifier, date and times, workarea, location, summary text, and description text. This cannot be changed. Records for
the previous week and the next 2 weeks will be included in the feed. Only enable these if you are happy for this data to
be exported in this way.

When you create a diary feed, Lamplight will generate a long, unique URL that you enter into your calendar app. Anyone
with this URL will be able to view the data - there's no additional login step, and it's not possible to add one.

Also, some calendar apps allow you to publish calendars more publicly, including your Lamplight diary feed, and this
tends to be controlled within the calendar app. Your staff may need to be made aware of this so that data is not
inadvertently shared.

Operators can create as many diary feeds as needed, and each can use various filters to limit the data provided in the
feed.

### Limit access to profiles for particular operators - 'My User' restrictions

The next section allows you to control access to certain profiles by certain database operators.

Database operators can be linked to other profiles (such as clients on their caseload) using the built-in ‘My User’
relationship (this may have been renamed in your system, perhaps something like 'caseworker' or similar). With the ‘My
User’ restriction enabled, database operators with lower access levels will only be able to see information about the
profiles that they are related to as 'My User's. In the sections below, these database operators are referred to as '
affected operators'.

Operators at higher access levels will not be affected by these restrictions at all.

#### How should access to profiles be controlled?

There are four options here. The default is no restriction - operators will be able to see all profiles.

The first option restricting access is '1) Only allow access to profiles linked via "my user" relationships'. Affected
operators will be able to see their own profile, and only other profiles if they have a current 'my user' relationship.
Either these relationships will be created by a higher-level operator, or, if the 'newly added profiles' option below is
selected, profiles that the operator created.

The second option applies this restriction only to certain profile roles. Select '2) Disallow access to profiles with
one of roles selected below, unless they are a "my user"' and choose the profile roles in the 'Which types of profile
should access be restricted to?' field lower down. With this option, the "my user" restriction only applies to profiles
with the chosen roles. So an affected operator might be able to view all referring organisations regardless of any
relationships, but only service users if they are part of their caseload.

The third option, '3) Disallow access to all profiles with one of the roles selected below' does not look at
relationships at all. Affected operators will not be able to see profiles of the type(s) selected. This would allow you
to limit access to funder profiles by staff, for example.

#### Restrict operators below manager level to only view {{activity}} and {{linked case}} records linked to the "my users" they are linked to.

Similar to the above restriction, this restricts access to all {{work}} and other {{activity}} records so that affected
operators will only be able to see records relating to people who are linked to them with a 'my user' relationship. This
relates to the main menu options under 'activity -> view'.

Whichever option is selected here, an affected operator will only be able to see the names of their 'my users' in the
attendance table for an {{activity}} record they can view. So there may be 10 people listed on an {{activity}} record,
but an affected operator may only be able to see three of their names.

The options in this section are:

**No restriction**
Operators will be able to see all {{activity}} records they would be able to without the 'My User' restriction.

**Show records I am listed on, or my users are listed on, or which have no Service Users Attending**
Affected operators will be able to see {{activity}} records that:

- they are listed on, or
- have at least one of their "my users" listed on, or
- have no-one listed using attendance role 'Service User' and type 'Attended'.

They would be able to see a record with just another staff member listed (with attendance role 'staff'), for example, or
an empty record.  **Please note** this uses the attendance role and type, not the type of profile (which isn't taken
into account at all).

**Show records I am listed on, or my users are listed on, or which have no-one listed at all**
Affected operators will be able to see {{activity}} records that:

- they are listed on, or
- have at least one of their "my users" listed on, or
- have no-one listed on at all.

**Only show records I am listed on, or my users are listed on**
Affected operators will be able to see {{activity}} records that:

- they are listed on, or
- have at least one of their "my users" listed on. Records with no attendees will not be visible with this option.

#### If using "My Users" restriction above, should newly added profiles be made a "my user".

By choosing this option, when a database user creates a new profile in the system, it will automatically create a
relationship with them as 'my user'. This is to prevent the need for another operator with a higher level of access to
go in and create the relationship before they can edit information in the profile.


#### Implications of using the 'my users' restriction

Operators affected will not be able to see profiles that they don't meet the rules for.  They may also not see {{activity}}
records depending on your settings.  This can cause confusion if it's not explained to the team.  It's also possible
to 'lose' access to a profile if it's edited by someone else, or the relationships are changed - again this needs explaining.

A higher level operator will need to assign profiles to operators (by creating relationships) for them to be able
to work with them.

Restricted profiles will be hidden from searches, listings, duplicate checks, and {{group}}s.

Manual {{group}}s and {{waiting list}}s may not be edited by someone affected by the my user restriction because
they may inadvertently remove profiles because they don't have access to them.


##### Tags
Security

###### core module
