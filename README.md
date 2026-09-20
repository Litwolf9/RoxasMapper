ROXAS MAPPER
==============================================================

Hey, thanks for grabbing Roxas Mapper!

Here's the quick version of what it does: it takes a name and
swaps some letters for unicode lookalikes - characters that
look almost identical but are technically different. Then it
checks those variations against Epic Games, so you can snag a
name that looks like the one you wanted even when the normal
spelling is already taken. Find one you like and it can apply
it to your account for you.


--------------------------------------------------------------
 GETTING STARTED
--------------------------------------------------------------

Two clicks and you're going:

 1. Download RMInstaller.bat and double-click it. It sets
    everything up on its own - give it about 5 to 10 minutes
    the first time, since it downloads a browser in the
    background.

 2. When it finishes, run RoxasMapper.py (double-click it, or
    type "python RoxasMapper.py" if you like the command line).

The installer tidies up after itself, so once it's done the
only thing left in the folder is RoxasMapper.py.


--------------------------------------------------------------
 WILL IT RUN ON MY PC?
--------------------------------------------------------------

If your computer runs Windows and can run Python, you're set.
Nothing fancy needed.

To be specific:

 - Windows 10 or 11
 - Python 3.8 or newer from https://www.python.org/downloads/
   - and please TICK "Add Python to PATH" during the install
     (that one checkbox trips up a lot of people)
 - An internet connection
 - Around 200 MB of free space, mostly the browser download

No gaming rig required. If Python runs, Roxas Mapper runs.


--------------------------------------------------------------
 WHAT THE INSTALLER ACTUALLY PUTS ON YOUR PC
--------------------------------------------------------------

Fair thing to ask - here's everything:

 - RoxasMapper.py - the program itself. The installer writes
   this file into the folder for you.

 - Playwright - a Python package that lets the tool open and
   drive a browser (that's how it checks and changes your
   Epic name).

 - Chromium - the browser Playwright uses. It's about 150 MB,
   which is why setup takes a few minutes.

Once it's installed and verified, RMInstaller.bat deletes
itself and leaves just RoxasMapper.py behind.


--------------------------------------------------------------
 FILES IT MAKES WHILE YOU USE IT
--------------------------------------------------------------

As you use the tool it saves a few small files right next to
RoxasMapper.py. These all live ON YOUR OWN COMPUTER - nothing
gets uploaded anywhere:

 - .epic_token.json         remembers your Epic login so
                            you're not signing in every time
 - .epic_playwright_profile the browser session it uses for
                            the Epic website
 - .roxas_first_run         a tiny marker so the welcome
                            screen only shows once
 - .roxas_config.json       remembers your color + banner
                            choice between runs

Want it all gone? Hit [L] Logout to clear your saved login and
session, or [U] Uninstall to remove everything the installer
added, RoxasMapper.py included.


--------------------------------------------------------------
 GETTING AROUND THE MENU
--------------------------------------------------------------

The commands are split into two little groups:

 Account
   [LN] Login       log in to your Epic account
   [L]  Logout      clear your saved login and browser session
   [U]  Uninstall   remove everything the installer added
                    (asks you to type UNINSTALL first, just to
                    be safe)

 Options
   [D]  Debug       flip on extra logging if something's up
   [C]  Customize   pick from 28 accent colors, or switch the
                    banner (Sea Salt, Roxas, or Nobody)
   [I]  Info        a quick rundown plus privacy notes
   [S]  Socials     jump to my Discord, X, YouTube, or TikTok
   [O]  Offline     look up name variations with no login
                    (no availability check, no name changes)

Anywhere else, just type a word and it'll generate the
variations for you.


--------------------------------------------------------------
 A COUPLE OF IMPORTANT THINGS
--------------------------------------------------------------

Everything stays local on your machine - I don't collect
anything. That said, NEVER share your Epic account info
(tokens, codes, passwords) with anyone, no matter what they
tell you. A login code is basically a key to your account.

And to be clear: this tool ISN'T affiliated with Epic Games
or anyone else. It's a free project I made, and it always
will be free.


--------------------------------------------------------------
 DISCLAIMER
--------------------------------------------------------------

I am NOT liable for any damage you cause to your own account
by using this tool. You use it at your own risk.

ALWAYS make sure you got this from my official GitHub:
https://github.com/Litwolf9

If you downloaded Roxas Mapper from anywhere else, it could
have been tampered with - don't trust it, and grab a clean
copy from the link above.


--------------------------------------------------------------
 COME SAY HI
--------------------------------------------------------------

 Discord:  @litwolf
 X:        @LitwolfYT
 YouTube:  @LitwolfYT
 TikTok:   @fnroxas

Enjoy it, and say hi sometime!

 - Hi / Litwolf


--------------------------------------------------------------
 LICENSE
--------------------------------------------------------------

Released under the MIT License - free to use, modify, and
share, just keep the credit. See the LICENSE file for details.

Copyright (c) 2026 Litwolf (https://x.com/LitwolfYT)
