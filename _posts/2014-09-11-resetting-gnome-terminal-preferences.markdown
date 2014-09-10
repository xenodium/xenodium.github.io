---
layout: post
title:  "resetting gnome terminal preferences"
categories: howto
---

why?
----

Had conflicting/forgotten configuration while setting color theme.

reset preferences
-----------------

gconftool --recursive-unset /apps/gnome-terminal

set .bash_profile
-----------------

export TERM="screen-256color"

Ensure .bash_profile is always read
-----------------------------------

gnome-terminal->Edit->Profiles...->Edit->Title and Command->X Run command as login shell

Bonus if you want solarized on your terminal
--------------------------------------------

http://codefork.com/blog/index.php/2011/11/27/getting-the-solarized-theme-to-work-in-emacs
