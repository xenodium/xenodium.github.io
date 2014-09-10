---
layout: post
title:  "resetting gnome terminal preferences"
categories: howto
---

why?
----

Had conflicting/forgotten configuration while setting color theme.


1. reset preferences

gconftool --recursive-unset /apps/gnome-terminal

2. Set .bash_profile

export TERM="screen-256color"

3. Ensure .bash_profile is always read

gnome-terminal->Edit->Profiles...->Edit->Title and Command->X Run command as login shell

4. Bonus if you want solarized on your terminal:

http://codefork.com/blog/index.php/2011/11/27/getting-the-solarized-theme-to-work-in-emacs
