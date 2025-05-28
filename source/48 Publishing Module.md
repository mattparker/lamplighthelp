# 48 The Publishing Module

The Publishing Module adds the ability to connect a website or application to Lamplight using your Lamplight API. 
You can use Lamplight's built-in features to do this, or create your own. You can publish data out from Lamplight,
or accept data in, or both.

If you use the Publishing Module you can link information entered in Lamplight to your public website.  For example, you might want:

- A staff directory, pulled from the staffing information in Lamplight.
- A directory of local voluntary organisations (especially for CVSs and the like).
- A searchable directory of local services for people seeking support.
- A ‘what’s on’ listing of forthcoming events.
- To accept referrals from your website directly into your system.
- To accept bookings to forthcoming events from your website.
- To use QR codes to allow people to register their attendance at events.

You choose what records and information to publish, so you are in full control of your data.

Your system administrator will need to setup the module before it can be used: [section 134](/help/index/p/134) explains how to do this.

### Widgets

You can create widgets within Lamplight that allow you to embed profile information, {{work}} record listings 
or {{referral}} forms on your website. To do this you'll need to copy and paste a single line of html code from {{Lamplight}} 
into your own website.  This is a very quick and easy way to start using the publishing module and doesn't require 
specialist knowledge. [Section 134.3](/help/index/p/134.3) explains how to create widgets within Lamplight, and how to use them on your website.

Widgets are a great place to start: this Customer webinar video gives an introduction to the module and shows
you how to get up and running with the publishing module really quickly. It's recorded in the old version of Lamplight, but
the principles are the same.  You can watch it here:

<iframe title="Report CodeSets webinar" width="640" height="564" src="https://player.vimeo.com/video/764557132?h=5f2c1eb0ad&badge=0&autopause=0&player_id=0&app_id=58479"
data-video-display="home" frameborder="0" allowFullScreen mozallowfullscreen webkitAllowFullScreen></iframe>

### Public sign-in

The publishing module includes a public sign-in page that displays published {{work}} records and allows your 
service users to sign in and out of them on the day using their email address or a {{Lamplight}} QR code.
[Section 134.4](/help/index/p/134.4) explains how this works in detail. You'll need to register the devices you're using 
for public sign-in. Once you've done this you can sign in to the relevant web page on that device to see the day's 
events and allow people to sign in and out of them.

### Full API access

The publishing module also provides an API which you can use to request data and specify how to present it, 
so that you can set up workflows that meet your precise requirements.  You'll need a software developer to set this up for you on your website.

Different organisations use the publishing module in very different ways, and need it to match the look and feel of
their public-facing websites.  The publishing module is designed to enable this: your website uses the Lamplight
API to request the information you need, and then presents it how you want. You will need a programmer to set up your 
website to do this: they will need to understand how to request the data, what form it is returned in, how your {{Lamplight}} 
system is set up, and want you need to achieve.

Assuming that you have the correct permissions and setup, the types of data that can be handled through the API are:

| Record type | View | Edit | Add new                                 |
| :---------  | :---------- | :---------- |:----------------------------------------|
| {{Work}}    | Yes (date /time; workarea; summary; description, but not attendance) | Yes - adding attendees | No                                      |
| {{Referral}} | No | No | Yes (accepting referrals via a website) |
| Profile | Yes - name, contact details, custom fields | Yes - name, contact details, custom fields | Yes                                     |
| {{Workarea}} | Yes | No | No                                      |
| Relationships | No | No | Yes                                     |
| Adding profiles to {{group}}s or {{waiting list}}s | No | No | Yes |


We’ve set up a whole website, <a href="https://mattparker.github.io/lamplight-phpclient/" target="_blank">https://mattparker.github.io/lamplight-phpclient/</a> 
which gives some working examples and documentation to show how the API works.  It’s aimed at developers and other 
technical types to show how to get the data out of Lamplight and on to your website.  It goes into full detail about 
what can and what cannot be done with the module.



###### publish module

