# 26.4.1    Setting up an Attendee payee rule.

> To add an attendee payee rule, click 'admin' -> system administration and click on 'set up charge module rules and policies'. Click the 'create new attendee payee rule' Button. 

To add an attendee payee rule, click 'admin' -> system administration and click on 'set up charge module rules and policies'. Click the 'create new attendee payee rule' button. 

![Setting up a {{work}} record charge rule]({{imgpath}}252a.png)

An attendee payee rule is very simple: the person or organisation listed on the {{work}} record pays. All you need to do is specify the amount: this can be a percentage or a fixed amount (in £s). 

If you specify a percentage, this will be a percentage of the remaining amount to be paid. As a simple example, you might set up a rule that has a rate of 100%, and then create a payee policy containing just this rule. This will mean that the {{person}} attending will pay the full amount as calculated by the charge policy used. 

However, if you have a payee policy with a rule that allocates 25% to another organisation (a funder, for example), and then the 'attendee pays 100%' rule, the attendee will be charged 100% of the outstanding amount - that is, 75% of the total amount - as 25% has already been charged to the funder. In other words, you can't create payments due for more than the amount charged. 

It is possible, however, to create policies that do not allocate the full charge. An attendee payee rule of 50% as the only rule in a policy will mean that only 50% of the charges calculated are allocated. To avoid this, you might want to create an 'attendee pays 100%' rule that is added as the last rule in all policies, to ensure that any 'underbilling' is allocated to the person attending. 

When you are finished click 'save' in the bottom right hand corner. You will return to the charge module admin menu. 

###### charge module

