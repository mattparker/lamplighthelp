# 26.2.7    Creating a {{group}} bands rule

> To set up a {{group}}-based charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create a new {{group}} bands charge rule' button. 

To set up a {{group}}-based charge rule, go to admin -> system administration -> set up charge module rules and policies. Click the 'create a new {{group}} bands charge rule' button. 

![Setting up a group- bands based charge rule]({{imgpath}}248a.png)

Section [26.2.1  Setting up charge rules - general points](/help/index/v/{{version}}/p/26.2.1) explains the 'name' and 'previous rules' fields. It's likely that you will want to tick the 'Should previous rules apply if there is no match using this rule?' box. 

The {{group}} bands rule allows you to charge people based on their membership of a particular {{auto group}}. This will be useful in order to provide an 'unwaged' rate, for example, or to charge based on the turnover of the organisation attending. The rule can contain several bands, each based on a {{group}} - you will need to set up the {{auto group}}s you wish to use first (see section [14.1.0  Creating an {{auto group}}](/help/index/v/{{version}}/p/14.1.0) for details). In the 'unwaged' example, you would need one {{auto group}} that checks for unwaged status. In the 'turnover' example, you would need one {{auto group}} for each band. The first {{group}} would be (for example) 'turnover below £100,000', the second 'turnover between £100,001 and £250,000' and a third 'turnover greater than £250,001'. 

When you have created your {{auto group}}s, you can set up the rule. Click on the first cell of the table to give the band a name. Click on the second cell ('{{Group}} to check membership of') and select the {{group}} you wish to use from the drop- down list. In the rate cell, enter a number or a percentage. Numbers are interpreted as amounts of money; percentages are of any amount calculated by a previous rule. So to charge unwaged attendees a flat £10, regardless of any previous rules, you would enter 10 in the rate box. To charge 20% of the full rate (calculated by previous rules), you would enter 20% in the rate box. 

![A simple {{group}}-bands based charge rule]({{imgpath}}248b.png)

To add another band, click the 'add row' button on the right of the table. If it is possible that someone may fall into more than one band, the order of the bands becomes important: the rule will stop at the first match. In other words, even if your {{group}}s are not mutually exclusive, the bands are - someone cannot be in two different bands. So you will need to specify the bands in order of priority. If this isn't an issue, {{Lamplight}} will be slightly faster if you put the 'most likely' bands first. In the turnover example, if you know that most of the groups are likely to fall into the large bands, you would put the 'large group' band first. 

When you are finished, click 'save' in the bottom-right hand corner. You will be taken back to the charging menu, and you'll see your new rule in the 'charge rules' section. 

###### charge module

