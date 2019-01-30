# 24.5.0    System Administration - publishing module

> As system administrator you have the authority and responsibility to set the permission levels for the types and details of information that may be transferred from {{Lamplight}} to the public facing site that has been granted permission to receive it. 

To set up and manage the publishing settings, go to the system administration section within the admin settings and under the **Manage Publishing settings**, click **manage publishing settings**. This will open a page with the different configuration settings split over a series of tabs.

![publisting settings]({{imgpath}}215a.png)

Tick or untick the boxes according to the information you wish to allow your system to publish. This is the first step in the tiered approach of settings, please note that when these have been ticked, all the information in your system is NOT automatically shared with your public-facing site (see section [24.1.0  Publishing module security](/help/index/v/{{version}}/p/24.1.0)).

Within this section, only contact details from within a profile can be published. Further information held within your custom tabs can also be published - see section [18.3.0  System Administration - Custom profile tabs and fields for {{people}}](/help/index/v/{{version}}/p/18.3.0) for more information.

If you are a multi-{{project}} set-up, on the {{project}} tab you can specify which {{project}}s these publishing settings apply to.

The API key and details tab are the credentials your website will need to access data in {{Lamplight}} - think of this as a username and password that your website needs in order to get information from {{Lamplight}} (see [24.1.0  Publishing module security](/help/index/v/{{version}}/p/24.1.0)). You will need to provide these to your web developer, or whoever manages your website. If you think that these credentials have been compromised you can generate a new API key by ticking the 'Generate a new API key' and clicking the 'Save' button. The new API key will then be displayed on this tab. 

###### publish module

