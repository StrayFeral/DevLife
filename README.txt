DevLife v1.0, May 2013
========================
(c)2013 Evgueni Antonov, http://ca.linkedin.com/in/eantonoff/
License: GPL v3, http://www.gnu.org/licenses/gpl-3.0.html

Thank you for downloading DevLife!

You may freely distribute and modify the file, as long as the program
remains free of charge.


WHAT IS THIS
------------------------
A text-based role-playing-like game, designed to run as a Vimscript.

In short: You take the role of a software developer working for a
software development company. Your daily tasks are only three:
- Work
- Create code backups
- Have fun

This is my first game ever and was created in no time, as an exercice
to learn Vimscript. It is not perfect and trough testing I've found it
is not well balanced, but it was never the point to make it perfect.

Enjoy!
Evgueni Antonov


WHAT DO I NEED TO RUN IT
------------------------
You need Vim (http://www.vim.org). 
This script was written for Vim 7.3 for Windows.
It is NOT tested on the Linux version.
It is not designed to be run when multiple windows and buffers are open.

If it haves any problems on Linux, please let me know.
I will upload this to GitHub, so for any bug-reports, please submit there.

So far, no bugs are discovered, if you discover one, please submit. If
you discover a way to better balance the game, please submit a feature
request.

Thank you!


HOW TO INSTALL
------------------------
Just copy the script file devlife.vim anywhere within Vim's path.


HOW TO SETUP
------------------------
Just edit the value on line 34: devlifeSavePath = 'your/savegames/path/'
Please make sure the path ends with a separator!
Example: 'c:\proj\hal9000\' or if on Linux: '/blah/proj/hal9000/'


HOW TO RUN IT
------------------------
In Vim:
:so devlife.vim
:call RunDevLife()

Or if you want you can set Vim shortcuts, simply put this in your
vimrc file:
:nmap \s :so devlife.vim
:nmap \b :call RunDevLife()

My own vimrc file is included with this package, so you can use it.

Then use \s to load the source and \b to run the game.
You may also specify your path to devlife.vim .


HOW TO PLAY
------------------------
Once you run the script, an intro-text would be shown with basic
instructions on how to play. The menu will be active. Press a menu-key
to select an option. You can press also "?" at any time to
invoke the help.

This game is designed to simulate being a text-file, so from a distance
your screen will look like this is just some text file. At any time also
you can choose "clear screen" or "boss key" (see help menu for the keys)

Basically everything which appears on the screen is appended to the
current Vim buffer, which is convenient if you want to make a screen-
shot or just copy-paste text later.


FREQUENTLY ASKED QUESTIONS
------------------------

Q: WHAT IS A BIEBERJUSTIN?
A: First of all Bieberjustin have absolutely nothing to do with, as
   you may guess, Justin Bieber. Absolutely nothing! The Bieberjustins
   are mythical creatures, set to live somewhere in the fifth dimension
   above the Earth, but sometimes tend to come in our universe trough
   hacking black holes. They are violent, evil (at least no report has
   ever been reported for a non-evil one) and are said to rob the
   ice-cream trucks, which circle the parks during summer. They usually
   eat blue slush, so their teeth are always blue.

Q: WHO IS HONEYBOOBOO?
A: Alana "Honey Boo Boo" Thompson is a small cute girl, living in USA
   and being known for participating in child beauty pageants, just
   like TLC’s Toddlers & Tiaras. She is nice and does no bad things
   to anybody.
