# 26.2.1    Setting up charge rules - general points

> Explains the common features of charge rules, and some tips to get them to do what you intend 

Almost all charge rules have two fields in common:

 1. Rule name
  2. Should previous rules apply if there is no match using this rule?

The rule name is what you'll see when composing rules into policies. Please remember that one rule can be re-used in several different policies, so it'll be easier if the name describes what it does, rather than how you think you might use it. So 'base flat 80' to describe a flat-rate charge rule that charges £80 is better than 'training standard rate'. 

To explain the second 'should previous rules apply', an example will be helpful. Imagine we have set up two rules: a flat-rate charge rule (for £50) and a role-based charge rule that says 'service users pay 100%'. We set up a policy that uses these two rules; the flat-rate rule first, then the role-based rule. 

Now when we come to use the policy, {{Lamplight}} will look at each {{person}} listed. First it will set the charge to £50. Then it will check their role. If it is 'service user', then the final charge will be 100% of £50. If it is something else, say a staff member, what should {{Lamplight}} do? We've only set our rule to do anything with service users. 

If the 'should previous rules apply' box was ticked, then if the rule does not match (because it's a member of staff), the previous (flat-rate) rule will apply, and they'll be charged £50. If the box was not ticked, they will be charged 0. 

In this example, we probably do not want to charge staff for attending, so will either leave the box unticked, or explicitly set the rates to zero (or whatever) in the role-based rule. But even if you do this, you'll need to update the rule if you ever add a new 'role' to the list. 

In general, it's likely that for attendance and role-based rules, you will not want previous rules to apply. For other types of rule, it's more likely that you will want previous rules to apply. 

Note that this does not apply to flat-rate rules: there is no conditionality in flat- rate rules, so there is no possibility that there will not be a match. In other words, previous rules can never apply to flat-rate rules. 

###### charge module

