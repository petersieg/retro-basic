# retro-basic
Retro Basic Interpreter in C

99.99..% the work from: https://github.com/slviajero/tinybasic/tree/main

Consider the repo above as the main repo! Please find new/updates/issues there.
I might as time allows make an update here from time to time. The creator Stefan is ok with my copy.
(I just did not wanted to do a normal fork, with 90% in it, that was not of my primary interest).

I just used the basic2/posix leaf to create a MAC DMG easy installer in Jan. 2026 from version 2.0.

Folders:

bas = only few examples basic source programs (.bas and .txt are both basic source code). More on above main repo.

doc = contains manual.md, the basic language manual for this interpreter. 

src = source code files

win = source code files for windows

basic_lion = under Mac OSX Lion compiled basic interpreter. 

basic_bigsur = under Mac OSX Big Sur compiled basic interpreter. 

basic_winxp.exe = under Windows XP with TDM-GCC 10.3.0 compiled basic interpreter. Since XP cmd does NOT interprete ANSI esc sequences, please load ANSICON before starting basic exe if you want to use cls, locate, etc. 

Find ANSICON here: https://github.com/adoxa/ansicon


basic_lion.dmg = DMG Image with basic application, ready to run/install(copy) to applications folder.

This basic_lion.dmg should run from Mac OSX Lion up to Mac OSX Big Sur.

