# 23.1.0    Setting up an {{Eval}}s Direct campaign

> Before you start, you will need the {{Eval}}s and {{Eval}}s Direct modules enabled on {{Lamplight}}.  A Datadirect campaign uses existing {{eval}}s.  If you want to use a new {{eval}} you'll need to set it up using the {{eval}}s module.  [(Evaluations 15.0.0)](/help/index/v/{{version}}/p/15.0.0)

A 'Campaign' is the name of a particular set of evaluation requests to invitees.  It may be a one off campaign following a training session for example, or you may use the same campaign for all activities of a particular type.  You can report on information across the campaign as a whole, or see answers broken down by a specific choice in one of the questions. 

To set up a DataDirect {{Eval}} Campaign, in the main menu go to {{work}} -> DataDirect -> {{eval}} campaigns -> and choose add.  You will see a screen like the one below.

![EvalDirect campaign]({{imgpath}}207a.png)

Complete each section:
__Campaign details__

* Select Evaluation: Choose the existing evaluation you want to use, or create a new one first through the {{eval}}s module.
* Title for the campaign: Choose a title which will allow you to identify this campaign. For example, you may have a generic 'training feedback' {{eval}} template set up, but the title might refer to the particular piece of training carried out (e.g. Health and Safety course May 2011).
 * Time and date starts and finishes: These define when your invitees will be able to complete the {{eval}} form.  If they try outside of these times, they will receive an error message.
 * Work Area: Responses will be entered directly into {{Lamplight}}, and so as with every other type of record, requires a {{workarea}}.  All responses to this campaign will be assigned to this {{workarea}}
 
 * 'Do you want to create a separate page for each invitee'
 This option is ticked by default.  {{Lamplight}} will create a unique url (website address) for each invitee.  Using this method you will be able to see who has responded and what they have said, and this information will appear in their profile.  It's good practice to ensure invitees know their responses are not anonymous.  If you untick this box, all invitees will receive the same link, give anonymous replies, and information will be held only in data direct, and not in profiles.
 
 * Do you want invitees to be able to use their web link more than once
If you send out individual emails (the box above is ticked) then you can choose one of these options for your email.

__Invitees__

Select the {{people}} you wish to complete the survey, in the same way that you would for other records ([Adding attendance 9.1.2](/help/index/v/{{version}}/p/9.1.2).

__Text and styling__

The final tab, 'Text and styling', will let you customise the appearance and content of the survey when your invitees visit the web address. The elements of the survey screen are, in order:

  1. The 'introductory text'. Appears at the top of the screen before the survey.
  2. The 'text to display at the bottom of the page', after the survey.
  3. Text to display after the information  has been saved.  This takes to a new page with this text on.
  
  4. Style.  What font you wish to use.
  5. Colour scheme (try them out)
  6. Do you want to display your logo. (If you have one uploaded)
  
System administrators can create customised designs if required, which you'll see reflected here.

###### datadirect module

Further reading
* [({{Eval}}s overview 15.0.0)](/help/index/v/{{version}}/p/15.0.0)
* [(Creating an {{eval}} 15.1.1)(/help/index/v/{{version}}/p/15.1.1)
* [Viewing {{eval data}} 15.1.2)(/help/index/v/{{version}}/p/15.1.2)
* [{{eval}} reporting 17.5.0)(/help/index/v/{{version}}/p/17.5.0)

