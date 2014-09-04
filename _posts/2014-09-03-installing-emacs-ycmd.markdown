---
layout: post
title:  "installing emacs-ycmd"
categories: howto
---

Installing [emacs-ymcd](https://github.com/abingham/emacs-ycmd) (work in progress):

Pre-install:
```shell
$  pip install requests
$  pip install enum34
$  brew install httpie

$  git clone https://github.com/Valloric/ycmd.git
$  git submodule update --init --recursive
$  ./build.sh --clang-completer --omnisharp-completer
```

Emacs package-install ycmd

Configure init.el:
```lisp
  (require 'ycmd)
  (setq ycmd-server-command '("python" "path/to/your/ycmd/ycmd"))
  (ycmd-open "path/to/your/.ycm_extra_conf.py")
```

Reference:

[https://github.com/Valloric/YouCompleteMe/blob/master/README.md#mac-os-x-super-quick-installation](https://github.com/Valloric/YouCompleteMe/blob/master/README.md#mac-os-x-super-quick-installation)
