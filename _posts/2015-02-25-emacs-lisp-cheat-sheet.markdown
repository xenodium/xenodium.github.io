---
layout: post
title:  "emacs lisp cheatsheet"
categories: emacs elisp
---

## Basics

(car LIST) ;; First element.  
(cdr LIST) ;; All but first element.  
(push NEWELT PLACE) ;; Add to beginning.  
(mapcar FUNCTION SEQUENCE) ;; Invoke 'FUNCTION for each in SEQUENCE.  
(while (search-forward "Hello") ;; Search/replace.  
  (replace-match "Bonjour"))  
