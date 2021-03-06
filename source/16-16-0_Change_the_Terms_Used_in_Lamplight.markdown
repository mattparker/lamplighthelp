# 16.16.0 <i class="fas fa-tools"></i> Change the Terms Used in {{Lamplight}}

> You can change a number of the terms used in {{Lamplight}} to match the language of your own organisation



It makes sense for the language you see in {{Lamplight}} to match the terms that you use in your organisation. There is an option to translate key terms and how they appear in your system.

- Go to 'admin -> system administration -> Customise Lamplight -> Change terms used in {{Lamplight}} for en_GB. If your system is translated into another language you may see other options for the language that you're changing - choose the appropriate one for your system.
- Here you will see a list of common terms used in your system, grouped by profiles, roles, types of activity, groups, other and form labels (used in {{activity}} records, such as {{work}} and {{outcome}}s).
- Find the term that you want to change. You will see the default term on the left, then a text box to the right of it. 
- Click in the text box and enter the term that you are going to use.


For example, in this system the people that we work with are currently called 'users'.
   
   ![Clients as 'Users'](16.16.0a.png)
   
We are changing that in system admin to 'clients'.
   
   ![Changing Language to Clients](16.16.0b.png)
   
   - Save your changes at the bottom of the page.
   - Refresh your system by pressing F5 on a Microsoft keyboard or Command R on a Mac.
   
Now when we see the term used in {{Lamplight}} it will show the word that you chose.  These changes apply for everyone using your system with the same language (i.e. 'en').
   
   ![User Changed to Client](16.16.0c.png)
   
If you can't find the term that you want to change in the list at the top of the page, scroll to the end where there is an 'Additional translations' box. 
- Click in the box under the last entry. 
- Add the current term that you would like to translate followed by a semi-colon (;), then the term you want to replace it with. 
 
![Translation an Additional Term](16.16.0d.png)

 - Again, save your changes at the bottom of the page, then press F5 or Command-R to refresh the system.  
 
 
### Using translations to add information to built-in forms

You can translate the labels of built-in form elements that appear in any of the forms using the 'Additional translations'.  For example, you could add 'Surname;Last name' to the additional translations, and when adding a new profile you'll see 'Last name' as the label on the form.

You can also add placeholder and description labels to these built-in form elements using translations. A placeholder is the 'shadow' text that appears in an empty text form element.  The description is the text that appears below a form element.

To add a placeholder to the Surname field, add 'Surname (placeholder);aka Family name' to the additional translations.  To add a description to the Surname field, add 'Surname (description);If the client is unwilling to give a surname, please ask just for an initial.' to the additional translations.

However, if you've done all of these (i.e. you have translated 'Surname' to 'Last name'), you'll need to use the **translated** version in your 'Additional translations':

Surname;Last name
Last name (placeholder);aka Family name
Last name (description);If the client is unwilling to give a surname, please ask just for an initial.

Entering a new profile will then look like this:

![Translating form elements and adding placeholders](16.16.0e.png)

 
### Different Translators

At the very bottom of this page is an option to change how the translation happens from the standard terms to your chosen ones.  For English you will almost certainly want to use the default.  If you are translating {{Lamplight}} into another language completely other options may be useful, depending on the language and how it's structured (some languages don't have capital letters, for example).

{{Lamplight}} has been translated into Swahili and Hindi, and can happily store data entered in other languages and glyphs (e.g. Chinese).

#### Literal Translator

The literal translator will translate an entire phrase as it appears in {{Lamplight}}.  Each field and label is a "phrase" - for example "How do you want Lamplight to translate phrases?".  You could enter this as a term to translate in the 'Additional translations' box above, and the label would be changed.

#### Keyword Translator

The keywords listed on the translations page will often appear within other phrases (for example "Filter by workarea").  The keyword "workarea" will often need to be translated on its own within the rest of the phrase. 

#### Which Translator to Use?

Take the sample phrase "Filter by workarea".

If you translate keywords first, then literal terms, {{Lamplight}} will:
 - translate "workarea" and substitute the translated term into the phrase (e.g. "Filter by department")
 - look for a translation for the entire phrase "Filter by department" and substitute this with the translated term (e.g. "Department selector").
 
If you translate literal terms first, then keywords, then {{Lamplight}} will
 - look for a translation for the entire phrase "Filter by workarea" and substitute this with the translated term
 - then filter any remaining keywords.
 
Keywords are enclosed in double curly brackets.



##### Tags
Advanced topics

###### core module
