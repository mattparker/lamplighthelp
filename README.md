# Lamplight help


The base text for the online Lamplight help system.  This text is then 
built on demand for individual customers, so that it is customised 
to their system:
* their language pack is used, so terms used in the text reflect their
system
* modules that are not in use are greyed out


## Overall process for making changes

To add content to the help manual, you will need to

1. clone this repo (once), or make sure your copy is up to date (frequently, pull)
2. make your changes
3. submit a pull request to the `review` branch
4. once changes have been reviewed, they'll be merged into the `master`

A separate build process will then take the text from here and update
customer help files and downloads.  This will happen nightly, so updates should
appear the following day.  If you want to rebuild immediately, go to 
https://lamplight.online/en/help/rebuild (when logged in).

Please make frequent commits - one commit should only have changes to one
page (file).  Reference issues in the commit message (e.g. "Updated
page on adding work records #123").


## Language pack for translations

The current set of terms that may be used and which should be translated 
are [listed](./language.markdown).  If additional ones are needed, you'll
need to speak to Matt.

Terms to be translated will respect the case, so {{Eval}} will be replaced
by Evaluation, and {{eval}} as evaluation.  Plurals should be outside the 
{{placeholder}}s (which is admittedly tricky for things like {{staff}}s).


## Format of a help manual page

Text of help pages is written in a limited markdown (see the [syntax guide](http://daringfireball.net/projects/markdown/syntax))
and then converted to html.

Pages files are currently named `chapter-section-subsection_Page_title.markdown`.  It
won't matter what they're called, but that seems a reasonable convention to follow.

Help pages should use the following format


    # 12.3.4    Page title, with a single '#' at the start.

    > An short paragraph giving a summary of the main content of the page.  Be sure to 
    remember the initial '> '.

    The main text of the help page.  This will need to include terms that
    can be translated, like {{Lamplight}}.

    Just keep writing...  Links to other pages should be inserted as links in the normal
    way [12.3.4  Title of the page linked to](/help/index/p/12.3.4).  To link to a Word or PDF version of a page, 
	append /format/docx or /format/pdf to the link.
	
	Historically links have needed a {{version}} placeholder, but these are no longer required and can be removed.  
	If it's left it'll just be ignored, so removing them is just for tidying up.

    Images are inserted like this:
    ![Text describing the image, including {{Lamplight}} placeholders](123a.png)
    i.e. as markdown images.  Images can be called anything, and should be saved in the /img folder 
	of this repository.  Historically they have needed an {{imgpath}} placeholder but this is no longer necessary
	and can be removed.

    You can tag pages with none, one or more tags.  To do so, add a '##### Tags' line, with each tag appearing on 
	a separate line below it, as shown below.


    ##### Tags
	Getting started
	System admin
	
	##### Links
	[You can also add links to other resources (which can be external links if appropriate)](http://www.whatever.com)
	[System admin](/en/help/index/p/tagged_System Admin)

    At the end, please put a tag that describes which module the page relates to (the line should start ######)

    ###### core|eval|comms|charge|costs|datadirect|library|publish|staff|waiting module


## Images

Images (screenshots) should be added to the img/ directory.  The number of an image 
no longer relates to anything (you can call them anything), but the letter (e.g. 123a.png)
was incremented within a single page of the manual - so 123a.png, 123b.png and 123c.png 
would all be expected to be on the same page.

## Tags

Please use tags from the following list (which is case sensitive):

 - Getting started
 - Next steps
 - Experienced user
 - Advanced topics
 - Time saving tips
 - System admin
 - Data protection
 - {{Report}}
 - {{Group}}
 - {{Activity}}
 - {{Profile}}
 
 The first four are intended to indicate the 'difficulty' of the page, and so any particular page should not
 use more than one of these.

	
All pages tagged with a particular tag will be listed if you visit https://lamplight.online/en/help/index/p/tagged_Profile
Note that tags will not be translated in the page address, and the {{}} removed.  However text on screen will be translated,
so you could visit the page https://lamplight.online/en/help/index/p/tagged_Group and see pages about 'Lists' (as the translation
of {{Group}}.
You can use whatever you like as a tag, but tags should be from the following list.  Any page should only have one
of the first four tags, intended to be in increasing 'difficulty'.
	
## Versions

There used to be two versions of the base text for the help manual - v0 and v1.  
There isn't any more (different repositories could be used if a customisation was needed)

/v/{{version}} and {{imgpath}} placeholders are old and no longer required (though won't do any harm
if left) and can be removed.


## Licence 


<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_GB"><img alt="Creative Commons Licence" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Lamplight Database help manual text</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/mattparker/lamplighthelp" property="cc:attributionName" rel="cc:attributionURL">Lamplight Database Systems Limited</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_GB">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.
