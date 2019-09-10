# 24.4.0 Expense Module: Reporting Using Cost Data Linked to the {{Staff}} Management Module

> The Expense Module can be linked to the {{Staff}} Management Module to allow the {{staff}} cost connected to a {{work}} record to be calculated as part of the overall costs for the work that you do

### Calulating Staffing Costs

**Adding the Staff Member's Hourly Wages**  

To be able to calculate the staffing cost, first you will need to add each staff member's hourly rate to their record.
- Go to the profile of the staff member whose hourly rate you want to add.
- Click on the 'Contract details' tab (you will only see this is you have the Staffing Module, and you are in the management hierarchy for this member of staff. For more on this see [29.1.0 Staff Management Module: Setup](/help/index/p/29.1.0).
- Click on the menu button to the left of the contract whose hourly salary you want to edit, or click 'add' to enter details of a new contract.
- Enter the rate into the 'hourly salary' box and click 'save'.

![Staff Management Hourly Salary Box](24.4.0a.png)

**Adding Staff Salary as a Cost to {{Activity}} Records**  

- Once you have added a staff member's hourly salary, this information used every time a {{work}} record is created.
- The calculation will be automatic, provided that:
   - The {{staff}} member's hourly wage has been entered into their profile, and that the contract period covers the date of the {{work}} record.
   - The {{staff}} member has been added to the attendance list.
   - The {{staff}} member's attendance type is 'attended' and their role is 'staff'.

**Using Staffing Costs for Reporting**

- Run the work report as usual (for more on this see [17.0.0 Reports](/help/index/p/17.0.0).)
- In the 'Report presentation' tab choose 'Cost data' as your 'Data to show'. 

![Choosing Cost Data in a Report](24.4.0b.png)

- Click 'Run' to generate your report. 
- The {{report}} will generate the following statistics:
   - Mean cost per user attending: this is a 'cost per head', calculated by taking the total cost for all {{work}} records included in the {{report}}, and dividing by the number of {{user}}s attending (i.e. 'Attendance type' is 'Attended', and 'Role' is '{{user}}').
   - Mean cost per session: this is calculated by dividing the total costs incurred by the total number of {{work}} records included in the report.
   - Total costs: the sum of the costs incurred.

![Total Costs Report Column](24.4.0c.png) 

**Viewing Costs for Individual Records**

- Go to '{{activity}} -> view -> {{work}}' (or other type of {{activity}} record as necessary).
- Right-click on the coloured header bar at the top of the table. This will give you a list of the available columns for the table. 
- Click  'Total cost'. This adds the cost column to your table. 
- If you would like to include this column in your default view for this table, open the column menu again and click on 'Save table columns layout'.
- You can follow this same process to view costs in an individual's {{work}} or other {{activity}} profile tabs.


###### costs module

