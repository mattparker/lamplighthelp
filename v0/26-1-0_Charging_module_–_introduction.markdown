# 26.1.0    Charging module introduction

> The charging module allows you to set charges for attending a {{work}} record, and then decide who should pay that charge. 

The charging module allows you to set charges for attending a {{work}} record, and then decide who should pay that charge. There is a great deal of flexibility in the way that charges are calculated, and the payments due can be split between different {{people}}. Once these payments have been allocated, they can be batched up into invoices and can then be exported into your own accounting software for billing and credit control purposes. 

The charging module is designed so that it's really quick and easy to use on a day to day basis. This does mean that setting it up is much more involved. 

For day-to-day use, when adding a {{work}} record you will see a {{charge}} tab, which lets you choose a charging policy and a payee policy for the record. 

![Charging policy in {{work}} record]({{imgpath}}1222.png)

Charging policies determine how much each {{person}} attending should be charged; Payee policies determine who should pay this charge. 

Both charge and payee policies can take various factors into account in their calculations. You create these policies to do what you need them to do. 

__Creating policies__

For example, you might have a charging policy that charges everyone £50, and a payee policy that says that the {{person}} attending pays the full amount. A more complex example of a charging policy would: 

 1. Use an hourly rate for the {{workarea}} chosen, a fixed amount for the location used, and the hourly rate for the staff present,
  2. If {{people}} attending are unemployed, charge them a fixed rate of £10,
  3. Gives a discount for {{people}} booking online before a certain date
  4. Only charges {{user}}s attending the full amount; staff are charged nothing and {{people}} that do not attend are charged 50%

A more complicated payee policy might say: 

  1. If the {{person}} attending lives in Westminster, charge Westminster Council 50% (we have a contract with them)
  2. If the {{person}} attending has a visual impairment we can charge £30 to a private Foundation that has given us a grant.
  3. Charge any remainder to the {{organisation}} linked to the person that attended

When you create a {{work}} record using these policies, {{Lamplight}} will calculate the amounts and payees, and they will appear on the {{charge}} tab of the relevant profiles, with a summary shown on the {{work}} record. 

By using these policies it is possible that the amount charged for someone attending a {{work}} record will not be the same as what they pay: indeed often the {{person}} attending will not pay anything. In these cases, the 'charge' should be thought of as the total amount paid by all parties (i.e. funders) for that person attending. 

__Stacking policies__

Although you can set-up mutiple rules in the same policy, and determine the order in which they enact, each person can only be affected by the first rule process.  For example, If the first rule in a policy charges a volunteer £10 based on their attendance, no further rules will be process for that person.  This is very important to bear in mind as you read through the rest of this help section.


These policies are set up by the system administrator. 

###### charge module

