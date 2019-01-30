# 12.1.5    {{Comm}}s - adding {{message}} content

> Your actual {{message}} is entered in the {{message}} content tab. 

Type in your text for the actual {{message}} in the {{message}} content tab. You can use the rich text editor (except with text messages): see section [4.4.0  Rich text editor](/help/index/v/{{version}}/p/4.4.0) for more help on how to use the editor.

The core system allows you to do basic mail-merge features, using name and address fields. On the text editor you will see a button with these fields: simply click on one on the drop-down menu to insert the relevant field.

If you have the {{comm}}s module you will have additional buttons on the editor toolbar. In particular you can use document templates and insert images from the library - see section [18.8.0  {{Comm}} templates](/help/index/v/{{version}}/p/18.8.0) for more help on setting these up.

![Using document templates]({{imgpath}}88a.png)

Note that the menu options on the editor vary. If you are communicating to people attending a {{work}} record, for example (see section [9.2.10  {{Comm}}](/help/index/v/{{version}}/p/9.2.10)) you will be able to include mail merge fields for that record.

Please be cautious of pasting text from another word document into the text editing tools. The text editor in {{Lamplight}} uses standard html and by default tries to filter any extra code. As this can have some unexpected results, there are some buttons to allow you to do HTML checks. 

![Using document templates]({{imgpath}}88b.png)

The first button lets you edit the HTML content of your message directly. 

The second button checks the HTML you have entered, and filters it if necessary. This filtering happens when you send/create the message, so clicking this button lets you double-check the content of your message. 

It's worth doing this after pasting text from Microsoft programs to check your message will look OK. In some cases your message will corrupt or even appear to disappear. In this case, there is a problem with the Microsoft formatting codes that you are pasting. You'll need to delete the content of your message, and then click the third button which switches the MS filter on or off. 

When this is unclicked (it's on by default) the editor will not run the filters and whatever you paste will be sent as it is. This should be OK for emails; but it is very likely to cause problems if you are creating letters; {{Lamplight}} translates HTML into Rich Text Format documents, but expects valid HTML to convert (which Microsoft code isn't). If you are needing to do this you may want to send a test email first. 

When you have completed your message, click the 'create/send' button in the bottom-right. The {{comm}} will be generated: if it's a document, a download will be created and opened; if an email you'll receive notification that the email(s) were sent. 

[View the video](/help/video/id/27)
###### core module

