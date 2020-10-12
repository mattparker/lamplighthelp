# 28.4.0 Publishing widgets

> Publishing module widgets allow you to display published records from Lamplight on your own website just by copying a single line of html to your website.


Publishing widgets are html iframe elements that display the published records from your system on your own website.  You don't need a software developer to do this: you create the widget in Lamplight system admin, and then copy and paste the html code to your own website.

To do this you'll need to be able to edit the html of your website.  Most website platforms like Wordpress allow you to do this, but if someone else controls your website you may need to ask them to insert the widget: but it really is just a case of pasting a single line of html Lamplight generates.

### Types of widget

You can create widgets that

 - list published {{work}} records
 - list published profiles
 - create new {{referral}} records
 
You can create as many widgets of each type if you need to.  For example, you may have one widget that lists your staff members, and another directory listing that shows other partner organisations who may be of interest to your web visitors.

Widgets can also include your own styles if needed - if you want to change the colour, font, or other layout elements, for example.  You'll need to include CSS statements to do this.  You may be able to copy these from your main website, but if not you may need some help from a web developer.  But the default styles should be enough for many uses.

Creating widgets does not alter the overall security settings for the publishing module.  For example, you will need to make sure that you've turned on 'allow publish {{work}} records' if you want to use a {{work}} record listing widget.  [Section 28.2](/help/index/p/28.2) explains how to change overall publishing settings.

### Creating and managing widgets

To see and add widgets go to admin > system admin > Publishing module > Manage publishing widgets that show published data on your website.  You'll see any widgets you already have, and buttons to create new ones.

![System administration - publishing widgets](28.4.0a.PNG)

Click the 'edit' or 'delete' buttons to change an existing widget.  Note that if you do make a change, it will take effect straight away.  If you're already using a widget on your website, it will be changed, and if you delete it, it will stop working immediately.

When you're ready to use a widget, copy the html code in the grey box and paste it into your website in the right place.

If you want to test a widget before including it in your website, you can copy the URL from the iframe (the bit starting https://lamplight.online/...), and view it in a browser - but not the one you're logged into Lamplight with (use a different browser or an incognito/private window).

#### Profile list widgets

To create a new profile list widget, click the 'profile listing' button at the top of the admin screen.  You'll see a popup window like this:

![System administration - creating a profile listing widget](28.4.0b.PNG)

The publishing feed name is just for your reference and is only shown in the system admin section.  CSS statements can be entered if needed.  You need to choose a profile role and type, and you can only choose one of each.  Save the widget, and you'll see the listing of all widgets and the html code you need.

Without any custom CSS, the profile listing will look like this:

![Profile listing widget](28.4.0c.PNG)

The image is from [www.gravatar.com](https://www.gravatar.com) - a public system that allows you to associate an image with your email address.  If the email address has a gravatar image associated with it, it will be displayed.  The search box in the top-right corner will search the published data for profiles.


#### Accept {{referral}} widget

To create a widget that will allow people to create {{referral}} records through your website, click the 'accept {{referral}}' button at the top.  These widgets cannot be configured beyond the name and css:

![Publishing - creating an accept {{referral}} widget](28.4.0d.PNG)

Without any custom CSS, the accept {{referral}} widget will look like this:

![Accept {{referral}} widget](28.4.0e.PNG)

The referral topic select box lists your {{workarea}}s.  The {{referral}} record that's created will try and match the profile by email address, and include the text from the 'details' in the '{{referral}} reason'.

#### {{Work}} record listing widget

To create a widget that will show a list of published {{work}} records click the '{{work}} record listing' button at the top.  

![Publishing - creating a {{work}} record listing widget](28.4.0f.PNG)

You can optionally add a filter for {{workarea}} here, to only show records for one or more {{workarea}}s.  If you want to show all, leave this unticked.

Without any custom CSS, the {{work}} record listing widget will look like this:

![{{Work}} record listing widget](28.4.0.g.PNG)

The 'Title of record for publishing' from the {{work}} record is the main title, with date, time and {{workarea}} displayed below.

