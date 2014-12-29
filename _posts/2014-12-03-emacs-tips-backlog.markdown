---
layout: post
title:  "emacs tips backlog"
categories: emacs tips dev
---

Emacs tips for me to try...

## Melpa recipe format
[https://github.com/milkypostman/melpa#recipe-format](https://github.com/milkypostman/melpa#recipe-format)

## Emacs regex
[Emacs: Text Pattern Matching (regex) tutorial](http://ergoemacs.org/emacs/emacs_regex.html)

## NaturalDocs for JavaScript in Emacs
[Vineet's post](http://naiquevin.github.io/naturaldocs-for-javascript-in-emacs.html)

## checkdoc
Checks buffer for doc strings file errors.

## Replace char with a newline
M-x replace-string RET ; RET C-q C-j.  
C-q (quoted-insert)  
C-j (newline)  

## Check out [smart-mode-line](https://github.com/Bruce-Connor/smart-mode-line)
[Sacha's sample usage](http://pages.sachachua.com/.emacs.d/Sacha.html)

## Toggling key bingings
[Ode to the toggle](http://oremacs.com/2014/12/25/ode-to-toggle/)

## Squashing Commits with Magit
[http://howardism.org/Technical/Emacs/magit-squashing.html](http://howardism.org/Technical/Emacs/magit-squashing.html)

## Search all info documentation
info-apropos  
emacs-index-search  

## Search Emacs lisp reference manual
elisp-index-search

## inline shell-command and shell-command-on-region
C-u M-!  
C-u M-|  

## describe-bindings
C-h b lists all bindings. Narrow down with occurr.

## Malabar-mode
[https://github.com/m0smith/malabar-mode](https://github.com/m0smith/malabar-mode)

## How to debug expanded elisp macros
[http://www.wisdomandwonder.com/link/9316/how-to-debug-expanded-elisp-macros](http://www.wisdomandwonder.com/link/9316/how-to-debug-expanded-elisp-macros)

## Moving by parens
For example, C-M-u Move backward out of one level of parentheses.
[https://www.gnu.org/software/emacs/manual/html_node/emacs/Moving-by-Parens.html](https://www.gnu.org/software/emacs/manual/html_node/emacs/Moving-by-Parens.html)

## Try out kurecolor
[https://github.com/emacsfodder/kurecolor](https://github.com/emacsfodder/kurecolor)

## Repeat last command
C-x z (and just z threreafter).

## Disable furniture
(menu-bar-mode -1)
(toggle-scroll-bar -1)
(tool-bar-mode -1)

## Query replace recursively  

* M-x find-dired RET
* Navigate to location, RET
* Add find argument (none of all files), RET
* t (select all).
* Q (query-replace).
* Enter search/replace terms.
* y/n for each match.
* C-x s ! (save all).  
  

## save-some-buffers
[C-x s ! (to save all)](http://www.gnu.org/software/emacs/manual/html_node/emacs/Save-Commands.html)

## set-selective-display
[http://www.gnu.org/software/emacs/manual/html_node/emacs/Selective-Display.html](http://www.gnu.org/software/emacs/manual/html_node/emacs/Selective-Display.html)
