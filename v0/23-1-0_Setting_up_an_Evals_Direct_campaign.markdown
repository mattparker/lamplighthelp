# 23.1.0    Setting up an {{Eval}}s Direct campaign

> Before you start, you will need the {{Eval}}s and {{Eval}}s Direct modules enabled on {{Lamplight}}, and you'll need to have set up your {{eval}} template already (see section [15.0.0  {{Eval}}s module overview](/help/index/v/{{version}}/p/15.0.0) for more help with this). 

A Datadirect campaign uses existing {{eval}}s.  If you want to use a new {{eval}} you'll need to set it up using the {{eval}}s module.  ([Evalusations 15.0.0](/help/index/v/{{version}}/p/15.0.0)

A 'Campaign' is the name of a particular set of requests.  It may be a one off campaign following training for example, or you may use the same campaign for all activities of a particular type.  You can report on information across the campaign as a whole, or see answers broken down by a specific choice in one of the questions. 

To set up a DataDirect {{Eval}} Campaign, in the main menu go to {{work}} -> DataDirect -> {{eval}} campaigns -> and choose add.  You will see a screen like the one below.

![EvalDirect campaign]({{imgpath}}207a.png)

Complete each section:

* Select Evaluation: Choose the existing evaluation you want to use, or create a new one first through the {{eval}}s module.
* Title for the campaign: Choose a title which will allow you to identify this campaign. For example, you may have a generic 'training feedback' {{eval}} template set up, but the title might refer to the particular piece of training carried out (e.g. Health and Safety course May 2011).
 * Time and date starts and finishes: These define when your invitees will be able to complete the {{eval}} form.  If they try outside of these times, they will receive an error message.
 * Work Area: Responses will be entered directly into {{Lamplight}}, and so as with every other type of record, requires a {{workarea}}.  All responses to this campaign will be assigned to this {{workarea}}
 
 * If the 'Do you want to create a separate page for each invitee' box is ticked (which it is by default), {{Lamplight}} will produce a separate url (website address) for each {{person}} you invite to complete the form. This means that {{Lamplight}} will know who has completed it, and when, and can store their response in their {{Lamplight}} profile. It also means you use the next drop-down to control whether they may enter one response or many. If you untick this box, {{Lamplight}} will generate a single url for the campaign, which anyone who knows it may use.

On the next tab 'Invitees', you select the {{people}} you wish to complete the survey, in the same way that you would for other records (see section [9.1.2  Adding attendance details to a {{work}} record](/help/index/v/{{version}}/p/9.1.2) for more help with this).

The final tab, 'Text and styling', will let you customise the appearance and content of the survey when your invitees visit the web address. The elements of the survey screen are, in order:

  1. Your logo (if the checkbox is ticked)
  2. The campaign title (from the first tab)
  3. The introductory text
  4. The questions from the {{eval}}
  5. The 'text to display at the bottom of the page'

and once they have completed the {{eval}} and clicked 'save', they will see the 'text to display after their information has been saved'. The styles available are built-in: serif and sans-serif are clear and simple layouts using serif (Times New Roman) and sans-serif (Arial) fonts. System administrators can create customised designs if required. 

###### datadirect module

