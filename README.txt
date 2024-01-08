Mirror URL: http://www.vim.org/scripts/script.php?script_id=4583

DevLife v1.1, Jan 2024
========================
(c)2024 Evgueni Antonov, https://www.linkedin.com/in/eantonoff/
License: GPL v3, http://www.gnu.org/licenses/gpl-3.0.html

Thank you for downloading DevLife!

You may freely distribute and modify the file, as long as the program
remains free of charge.


CHANGELOG
------------------------
2024-01-07: v1.1 Updated for Vim 8.2, tested on Lubuntu 22.04
2013-05-10: v1.0 Initial version release for Vim 7.3, tested on Windows 7


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
This script was written for Vim 7.3 for Windows 7 and is last fixed for
Vim 8.2 and tested on Lubuntu 22.04.
It is not designed to be run when multiple windows and buffers are open.

I will upload this to GitHub, so for any bug-reports, please submit there.

So far, no bugs are discovered, if you discover one, please submit. If
you discover a way to better balance the game, please submit a feature
request.

Thank you!


HOW TO INSTALL
------------------------
WINDOWS:
Just copy the script file devlife.vim anywhere within Vim's path.

LINUX:
mkdir ~/.vim/plugin
cp <DOWNLOADED_PATH>plugin/devlife.vim ~/.vim/plugin


HOW TO SETUP
------------------------
No need to do anything. But if you want to change your savegame path,
just edit the value on line 40: g:savegamePath = '/tmp/'
Please make sure the path ends with a slash!
Example: 'c:\proj\hal9000\' or if on Linux: '/blah/proj/hal9000/'


HOW TO RUN IT
------------------------
RUN ON VIM 8.2:
:call RunDevLife()

RUN ON VIM 7.3:
:source devlife.vim
:call RunDevLife()

Or if you want you can set Vim shortcuts, simply put this in your
vimrc file:
:nmap \s :so devlife.vim
:nmap \b :call RunDevLife()

NOTE:
It seems Vim 8 loads automatically the plugins, so no need to load the source.

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
