---
layout: post
title:  "emacs tips backlog"
categories: emacs tips dev
---

### Emacs key bindings in Ubuntu
[http://promberger.info/linux/2010/02/16/how-to-get-emacs-key-bindings-in-ubuntu/](http://promberger.info/linux/2010/02/16/how-to-get-emacs-key-bindings-in-ubuntu/)

## Org Protocol
Irreal's [post](http://irreal.org/blog/?p=3594) and Or Emacs's [post 1](http://oremacs.com/2015/01/07/org-protocol-1/) and [post 2](http://oremacs.com/2015/01/08/org-protocol-2/)

### Try out nxml-mode

### Building Emacs 24.4 on Linux
sudo apt-get install texinfo build-essential xorg-dev libgtk-3-dev libjpeg-dev libncurses5-dev libgif-dev libtiff-dev libm17n-dev libpng12-dev librsvg2-dev libotf-dev
./configure --with-gtk --prefix=/your/fav/prefix

### Jumping around tips
At [zerokspot](http://zerokspot.com/weblog/2015/01/07/jumping-around-in-emacs/)

## ace-jump-mode and helm-swoop combined
See Sacha's [post](http://sachachua.com/blog/2015/01/emacs-kaizen-ace-isearch-combines-ace-jump-mode-helm-swoop/) on ace-isearch.

### use-package post
At [lunaryorn](http://www.lunaryorn.com/2015/01/06/my-emacs-configuration-with-use-package.html)

### Static blog
[org-page](https://github.com/kelvinh/org-page)

### youtube-dl for Emacs
[Details at or emacs](http://oremacs.com/2015/01/05/youtube-dl/)

### Clang indexing tool
[clang-tags](http://ffevotte.github.io/clang-tags/)

### Project management for C/C++
[Malinka](https://github.com/LefterisJP/malinka)

### Git modes
See [git-modes](https://github.com/magit/git-modes)

### Lots of org links
Found at [dain.io](http://dain.io/blog/2014/12/31/why-should-developers-and-managers-use-emacs/)

### Create custom theme
[See Trường's post](http://truongtx.me/2013/03/31/color-theming-in-emacs-24/)

### GTD Emacs workflow
[Charles Cave's notes](http://members.optusnet.com.au/~charles57/GTD/gtd_workflow.html)

### Simplify file transformations
With [make-it-so](https://github.com/abo-abo/make-it-so)

### [lispy](https://github.com/abo-abo/lispy)
For LISP editing.

### [lazyblorg](https://github.com/novoid/lazyblorg)
For simplifying blogging.

### Continue comment blocks
M-j (indent-new-comment-line).

### O(1) link jump
[Using ace-link](http://melpa.org/?utm_source=dlvr.it&utm_medium=twitter#/ace-link)

### Choosing magit repo
C-u C-x g (magit-status).

### Skeletor
[https://github.com/chrisbarrett/skeletor.el](https://github.com/chrisbarrett/skeletor.el)

### Melpa recipe format
[https://github.com/milkypostman/melpa#recipe-format](https://github.com/milkypostman/melpa#recipe-format)

### Emacs regex
[Emacs: Text Pattern Matching (regex) tutorial](http://ergoemacs.org/emacs/emacs_regex.html)

### NaturalDocs for JavaScript in Emacs
[Vineet's post](http://naiquevin.github.io/naturaldocs-for-javascript-in-emacs.html)

### checkdoc
Checks buffer for doc strings file errors.

### Replace char with a newline
M-x replace-string RET ; RET C-q C-j.  
C-q (quoted-insert)  
C-j (newline)  

### Check out [smart-mode-line](https://github.com/Bruce-Connor/smart-mode-line)
[Sacha's sample usage](http://pages.sachachua.com/.emacs.d/Sacha.html)

### Toggling key bingings
[Ode to the toggle](http://oremacs.com/2014/12/25/ode-to-toggle/)

### Squashing Commits with Magit
[http://howardism.org/Technical/Emacs/magit-squashing.html](http://howardism.org/Technical/Emacs/magit-squashing.html)

### Search all info documentation
info-apropos  
emacs-index-search  

### Search Emacs lisp reference manual
elisp-index-search

### inline shell-command and shell-command-on-region
C-u M-!  
C-u M-|  

### describe-bindings
C-h b lists all bindings. Narrow down with occurr.

### Malabar-mode
[https://github.com/m0smith/malabar-mode](https://github.com/m0smith/malabar-mode)

### How to debug expanded elisp macros
[http://www.wisdomandwonder.com/link/9316/how-to-debug-expanded-elisp-macros](http://www.wisdomandwonder.com/link/9316/how-to-debug-expanded-elisp-macros)

### Moving by parens
For example, C-M-u Move backward out of one level of parentheses.
[https://www.gnu.org/software/emacs/manual/html_node/emacs/Moving-by-Parens.html](https://www.gnu.org/software/emacs/manual/html_node/emacs/Moving-by-Parens.html)

### Try out kurecolor
[https://github.com/emacsfodder/kurecolor](https://github.com/emacsfodder/kurecolor)

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
  
  

### save-some-buffers
[C-x s ! (to save all)](http://www.gnu.org/software/emacs/manual/html_node/emacs/Save-Commands.html)

### set-selective-display
[http://www.gnu.org/software/emacs/manual/html_node/emacs/Selective-Display.html](http://www.gnu.org/software/emacs/manual/html_node/emacs/Selective-Display.html)
