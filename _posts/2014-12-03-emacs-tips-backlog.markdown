---
layout: post
title:  "emacs tips backlog"
categories: emacs tips dev
---

Random tips to try, which I would likely forget otherwise.

### Repeat last command

C-x z (and just z threreafter).

### Disable furniture

(menu-bar-mode -1)
(toggle-scroll-bar -1)
(tool-bar-mode -1)

### Query replace recursively

* M-x find-dired RET
* Navigate to location, RET
* Add find argument (none of all files), RET
* t (select all).
* Q (query-replace).
* Enter search/replace terms.
* y/n for each match.
* C-x s ! (save all).

### [save-some-buffers:](http://www.gnu.org/software/emacs/manual/html_node/emacs/Save-Commands.html) C-x s ! (to save all).

### [set-selective-display](http://www.gnu.org/software/emacs/manual/html_node/emacs/Selective-Display.html)

