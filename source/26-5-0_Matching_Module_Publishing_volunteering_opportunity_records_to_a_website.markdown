# 26.5.0 Matching Module - Publishing {{Volunteering Opportunity}} Records to a Website

> If you want to embed a searchable list of {{volunteering opportunity}} records on your website or elsewhere you can create 'API feeds'

The Matching Module gives you the option to publish {{volunteering opportunity}} records publicly. You don't need to have the Publishing Module for this to work. The easiest way to advertise your opportunities is to create 'feeds' - embeddable widgets that you can copy and paste into your website quickly and easily.  You set up these feeds with a few starting criteria within {{Lamplight}} - you will need to be a System Administrator to do this.

For {{volunteering opportunity}} records to appear in the API feeds, you will need to choose to 'publish' when you create them ([see section 26.2.1](/help/index/p/26.2.1)).

### To Create a New Feed

- Go to admin > system  administration and in the 'Matching Module' section click 'create new API feed'.  (If you can't see this option, please contact Lamplight).
- You will see any feeds you have already set up, and below that a form to create a new one:

![Create new {{volunteering opportunity}} feed](26.5.0a.PNG)

#### Feed Name
This is just for your reference. You can create multiple feeds for different purposes (perhaps a small 'near us' widget on a home page, and a full search form on a separate page).  Give your feed a name that will remind you what it is for.

#### Include a Search Form?
A simple search form can be embedded so that people using your site can narrow down the results they see.

#### Postcode to Centre Requests Around
You can use the geocoded address of the {{opportunity provider}} (or the {{volunteering opportunity}} itself) so that you only show records centred on the postcode you provide here. You will need to specify a maximum distance from this point for it to take effect.

#### CSS Files to Include in the Header
By default, the API feed is in well-structured html with no styling, so that it can take on the styles of your own site. See [section 26.5.1](/help/index/p/26.5.1) for more technical details about how the response will be structured.

Any CSS files you specify here will be included in the head element of the embedded iframe, so you can reference the CSS of your main site if you want to.

Click 'save' when you are done and you will see something like this:

![Created {{volunteering opportunity}} feed](26.5.0b.PNG)

Copy and paste the html (the bit in the box starting &lt;iframe) to your own website and you should see {{volunteering opportunity}} records immediately.


###### match module
