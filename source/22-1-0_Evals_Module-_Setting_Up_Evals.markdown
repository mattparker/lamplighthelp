# 22.1.0 {{Eval}}s Module: Setting Up {{Eval}}s

> A System Administrator can set up new {{eval}} templates for you to use in {{Lamplight}}



### To Set Up a New {{Eval}}
#### Adding an {{Eval}} in System Admin

- Click ‘admin’ in the main menu, then ‘system administration’.
- Scroll to the bottom 'Module Administration' section, find the '{{Eval}}s Module' box and click on ‘Manage {{eval}} templates’.
- The structure of this page will be familiar to those who have edited custom fields in profiles or records, and it works in the same way as those pages. 
- The items currently in the list will show in boxes on the page. Above these are 'add new {{eval}}' (to add a single {{eval}}) and 'bulk add {{eval}}' (to add a number of {{eval}}s) buttons. 

![System Admin {{Eval}}s Page](22.1.0a.png)

**If you are adding a single {{eval}}:**
   - Choose 'add new {{eval}}', then type the name of the {{eval}} in the 'Text' box. If you have {{project}}s in your system, you can also choose which ones it will be available to.
   - Click 'Update'. You will see it added to the list. You will now need to add questions (see below). 
   - Please remember that until you click 'save all changes' at the top or bottom of the main page this new {{eval}} has not been saved. (You can make all the changes you need on the page without saving in between, but you must not navigate away from the page before saving or all the changes will be lost.)
**If you are adding a number of {{eval}}s:**
   - Choose 'bulk add {{eval}}', then type in the name of each {{eval}} separated by a semi-colon (;). You do not need spaces between each one. For example, 'Training feedback;Staff management {{eval}};End of year checklist'.
   - When you have listed them all, click 'add all'. You will see them added to the list - check that they are all as you expected. You will now need to click on each in turn to add the questions - see below.
   - Please remember that until you click 'save all changes' at the top or bottom of the main page this new {{eval}} has not been saved. (You can make all the changes you need on the page without saving in between, but you must not navigate away from the page before saving or all the changes will be lost.)

#### Adding Questions to the {{Eval}}

**To add a single question:**

![The {{Eval}} Fields Dialogue Box](22.1.0c.png)

- In your new {{eval}}, click on the 'add new question' button. 
- The question itself goes in the 'Enter question text' field.
- If you tick the 'Is this question required?' field, then it will not be possible for respondents to save the {{eval}} until they have recorded an answer this question. 
- Placeholder text will appear in the text box for a text-based question (for example 'Add the reason here') if you choose that field type.
- Descriptive text can be shown below the field as an explanation (for example 'only complete this if the previous answer was 'no').
- Using the ‘Type’ field, select the type of field you wish to use. The options are as follows:
   - Select box: a drop-down list allowing a single selection.
   - Multi-select box: a drop-down box allowing the selection of multiple items (by holding Ctrl).
   - Text box: a single-line text-entry field.
   - Text area: a larger, rectangular text-entry field that can be resized.
   - Date selector: allows date, month and year to be specified.
   - Checkbox: a single option with a box that can be ticked.
   - Radio button: a single option with a circular button that can be ticked.
   - Date/time selector: allows date, month, year and time to be specified.
   - Rich text editor: the largest text-entry field, with formatting options.
   - Number box: a field that only accepts numbers with no spaces (if you need to allow spaces, use a text box).
   - Date of birth selector: like the date selector, but displays age when viewing.
   - Caption: a large, bold heading (does not record information from respondents).
   - Fixed text box: a line of regular text used as a guide or sub-heading (does not record information from respondents).
   - Year selector: allows a year to be specified.
   - Radio buttons select-one: a series of options with circular buttons, only one of which can be selected, also offering a ‘none’ option.
   - Checkboxes select-many: a series of options with checkboxes, one or more of which can be selected.
   - Charity number lookup: a text field where you can enter an English charity number, which then provides a link to the charity page on the Open Charities site.
   - Twitter name: a text field in which to enter a Twitter name, which provides a link to the Twitter profile.
   - Web address: a text field in which to enter a web address, which provides a link to the website.

[Section 16.7.1](/help/index/p/16.7.1) has more information about custom field types.

- When you have finished, click the ‘Update’ button. Again, remember that any changes you make aren't saved until you click 'save all changes' at the top or bottom of the main page.
- Continue adding questions in this way until you have all that you need. 

**To bulk add questions:**
If you want to add a number of questions at the same time:
- Click the 'bulk add question' button.
- Type all your questions in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. 

![Bulk Add Questions](21.1.0d.png)

- When you have finished, click 'add all'. They will appear in a list below the field name.

#### Adding Options to Select Questions

If any of the questions has a list of options, these must now be added. For example, your question may be 'On a scale of 1-5, how would you rate the training today?'

If it is a single question that you have just added you will see buttons allowing you to add options underneath it. If it is an existing question that you want to add more options to, or are editing, click on the question name then select the three dots on the right (the 'more' button) to see these 'add' options. 

**Adding a single option:**

- To add your options one at a time, click on the 'add new option' button. This opens a pop-up box where you type the text of your option (in the previous example, you might start with '1 - terrible'). 
- Click 'Update' when you have finished. 
- Continue adding all the options you need in this way.

#### Add a Number of Options at Once

- If you have a question which provides a number of different options, click on 'bulk add option'. 
- Type all your options in the text box, with a semi-colon (;) between each one. You do not need a space before each new one. For example, '1 - terrible;2 - poor; 3 - OK;4 - good;5 - excellent'.
- When you have finished, click 'add all'. They will appear in a list below the question.

### Changing the Order of {{Eval}}s, Questions and Options

You can re-order {{eval}}s, questions and options at any time. To reorder your {{eval}}s in the list: 

- Click on the name of the one you would like to move, then use the up and down arrows to the right of it to change its position in the list. 
- Alternatively you can reorder all of your {{eval}}s alphabetically by clicking on the 'sort' button above the list. Pressing this button once will arrange the evaluations in alphabetical order, while pressing again will sort them in reverse order.

The same principal applies to sorting questions (which can be moved up and down within their {{eval}}), and options (which can be reordered within the question):

- Click on the question or option that you  want to move, then use the arrow buttons to the right of it. 
- If you want to arrange all questions in an {{eval}} (or all options in a question) in alphabetical order, use the 'sort' button at the top of the list.

To find the 'sort' button which will order the questions within an {{eval}}, click on the {{eval}} name and the sort button will be displayed immediately below it. 

To find the 'sort' button which will arrange options within a specific question, click on the question name, then the button with three dots to the right of it. The 'sort' button appears at the top of the list of options.

### Testing Your {{Eval}}  

Once an {{eval}} has been created, try completing it to ensure everything is displayed as intended. 
- First refresh the page in your browser (by pressing F5 in Windows or Ctrl+R in OS X), and it will then be accessible through the main menu. 
- For more on completing {{eval}} information, please see [22.2.0 Adding and Editing {{Eval}} Responses](/help/index/p/22.2.0).


###### evaluation module

