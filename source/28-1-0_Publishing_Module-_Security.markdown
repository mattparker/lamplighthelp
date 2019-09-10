# 28.1.0 Publishing Module: Security

> The Publishing Module has multiple safeguards built in so that only the data you want to publish is accessible

When you decide to publish information from {{Lamplight}}, it creates web addresses that your website can request. {{Lamplight}} will respond to these requests with the relevant data: your web server can than process this information to display it on your site, in the style you design.

For these data requests to be successful, the following checks all have to pass:

  - Is the publishing module turned on?
  - Does the request have the correct credentials (equivalent to a username and password)?
  - Is the type of information requested (e.g. {{work}} records or profile information) allowed to be published?
  - Is the particular record being requested published (e.g. {{work}} record number 123)?

If all those checks pass successfully, {{Lamplight}} will look at which pieces of data can be published (e.g. name and phone number but not email address) and send it to your web server. 

Your data is still in your control, so you could add additional controls on your web server (e.g. don't display {{work}} records that have a particular {{workarea}}, or add a registration/signin mechanism so that only your members can see it). This approach gives you a very fine level of control about what data is published, and where to. 


###### publish module

