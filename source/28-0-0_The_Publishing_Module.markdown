# 28.0.0 The Publishing Module

> The Publishing Module adds the ability to connect a website or application to Lamplight using your Lamplight API. You can use Lamplight's built-in features to do this, or create your own



If you use the Publishing Module you can link information entered in Lamplight to your public website.  For example, you might want:

- A staff directory, pulled from the staffing information in Lamplight.
- A directory of local voluntary organisations (especially for CVSs and the like).
- A searchable directory of local services for people seeking support.
- A ‘what’s on’ listing of forthcoming events.

You choose what records and information to publish, so you are in full control of your data.  You also decide exactly how you want to present it on your website – we just link you to the data.

In addition you can, if you want, accept data into Lamplight.  For example, you can allow people to refer themselves through your website, book on forthcoming events, or update their profile information.

### Widgets

You can create widgets within Lamplight that allow you to embed profile information, {{work}} record listings or {{referral}} forms on your website. To do this you'll need to copy and paste a single line of html code from {{Lamplight}} into your own website.  This is a very quick and easy way to start using the publishing module and doesn't require specialist knowledge. [Section 28.4](/help/index/p/28.4) explains how to create widgets within Lampilght, and how to use them on your website.

### Public sign-in

The publishing module includes a public sign-in page that displays published {{work}} records and allows your service users to sign in and out of them on the day using their email address or a {{Lamplight}} QR code.  [Section 28.5](/help/index/p/28.5) explains how this works in detail. You'll need to register the devices you're using for public sign-in. Once you've done this you can sign in to the relevant web page on that device to see the day's events and allow people to sign in and out of them. 

### Full API access

The publishing module also provides an API which you can use to request data and specify how to present it, so that you can set up workflows that meet your precise requirements.  You'll need a software developer to set this up for you on your website.

Different organisations use the publishing module in very different ways, and need it to match the look and feel of their public-facing websites.  The publishing module is designed to enable this: your website uses the Lamplight API to request the information you need, and then presents it how you want. You will need a programmer to set up your website to do this: they will need to understand how to request the data, what form it is returned in, how your {{Lamplight}} system is set up, and want you need to achieve.  

Assuming that you have the correct permissions and setup, the types of data that can be handled through the API are:

| Record type | View | Edit | Add new |
| :---------  | :---------- | :---------- | :-------- |
| {{Work}}    | Yes (date /time; workarea; summary; description, but not attendance) | Yes - adding attendees | No |
| {{Referral}} | No | No | Yes (accepting referrals via a website) |
| Profile | Yes - name, contact details, custom fields | Yes - name, contact details, custom fields | Yes |
| {{Workarea}} | Yes | No | No |


We’ve set up a whole website, [http://www.lamplight-publishing.co.uk/](http://www.lamplight-publishing.co.uk/), which gives some working examples and documentation to show how the API works.  It’s aimed at developers and other technical types to show how to get the data out of Lamplight and on to your website.  It goes into full detail about what can and what cannot be done with the module.  

You will need a developer to add the Lamplight information to your website.  We strongly recommend that you and your developer review the [publishing website](http://www.lamplight-publishing.co.uk/) to confirm that you will be able to achieve what you need to with the module.


###### publish module

