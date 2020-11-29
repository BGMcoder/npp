# npp
Customization files for Notepad++

## Installation

### To install a User Defined Language (syntax highlighter) in Notepad++ 7+

Place the xml file in your Notepad++'s settings directory, which is usually this:
C:\Users\brgabriel.RCH\AppData\Roaming\Notepad++\userDefineLangs

### To install the syntax highlighter in Notepad++ older versions

In the main menu, go to View > User defined language...
Push the "Import..." button.
Browse to the syntax colouring file.  It may be either an .xml or a .udl file.
It will report "Import Successful"
Now, go and open one of the configuration files in Notepad++.
Voila!  Colour!

### RUN Commands

https://npp-user-manual.org/docs/config-files/#macros


## The Goodies

### Squiffy
Turn Notepad++ into your [Squiffy](http://textadventures.co.uk/squiffy) Editor!

There is a User-Defined Language, and a couple RUN commands (to build it from the RUN menu).
You see, for Squiffy, the actual squiffy editor doesn't have the greatest syntax highlighting and it's difficult to manage a large story, too.  So I use Notepad++ with my own squiffy UDL and functionlist.  I can easily navigate to any squiffy section - AND I can see a list of all the sections and passages right there in the list with their actual positions in the document.  Now, I also use my own html page based on the original one that Squiffy creates - since it never changes, you can alter it to your own fancy.  So I created a RUN command in Notepad++ to compile the story and just output the story.js (using [squiffy compiler](http://docs.textadventures.co.uk/squiffy/cli.html) via commandline).  Then all I have to do is push refresh in the browser to view the story with my custom css and whatever I want.  Overall, this makes composing stories much easier.

Another tip is to enable auto-completion in Notepad++.  This will allow you to autocomplete squiffy section and passage names!

### Aserisk

There are two kinds of UDLs for Asterisk.

- Asterisk.xml  - for .conf files
- AsteriskSys.xml - for .sys files
- and there is one for Polycom Config files - for .cfg files

Since other kinds of files are .conf, .sys and .cfg, you might skip the setting the file association for the UDLs if you use those other highlighters.  

### CSS
My css functionlist will properly display all elements even if they have linebreaks in between, or even if elements are declared on the same line.  You can read about it in the npp forum thread. https://community.notepad-plus-plus.org/topic/20397/is-there-a-good-css-class-parser
