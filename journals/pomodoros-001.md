04/03
---
Starting by reading: https://github.com/zv/SICP-guile
*(stopped at the desc. chapter by chapter to avoid spoilers)*

Links I want to look at later.
- [The Adventures of a Pythonista in Schemeland: Table of Contents](https://www.artima.com/weblogs/viewpost.jsp?thread=251474)

##### IDE?

Seems like I'm gonna need an IDE or something.

Let's not mess up my vim conf. I'll probably go with DrRacket or Emacs.

Emacs + Vim is a thing. Spacemacs and magit looks cool. So does orgmode.

BUT... I'm not in the mood for dealing with conf...

ok. let's not get fixated on this.

I'm gonna learn emacs so that I can use any LISP, and that'll solve the problem.
And I'm gonna use DrRacket when I'm learning Racket.
When in doubt, I don't chose. I just do everything at once.

First encounter with DrRacket: not smooth.

Let's do emacs.

# Which LISP

The article I was reading was recommending Guile

I've installed Guile 3 and Racket 8.

I have no idea what I'm doing to be honest.

...

I've installed clojure lol. with lein. I'm following instructions from Clojure for the Brave and True. Pretty smooth. There's an emacs tutorial inside. Maybe that could be useful.

...

---
Pomodoro n°4: --- Learning to carve LISP

Working through Clojure Brave and True to learn about emacs.

C-g to quit current command.

I don't want to learn new bindings...

But I've reached a section called Paredit, it seems what I was after was warping and slurping.

---
Pomodoro n°5: --- Learning to carve LISP (cont. )

- paredit mode
- barfing, slurping, warping,
- move to matching parentesis

The above is what I'm after. 
Let's do the following:
- [] check if vanilla emacs can do it...
- [] if yes, try one with vim keybindings...
Both answers are no. 

Let's find a vim plugin that does the job.

This one looks nice : https://github.com/eraserhd/parinfer-rust

Let's see if it works. 
Let's try the examples from here

IT WORKS !

commands for barfing etc.. https://shaunlebron.github.io/parinfer/#paredit-emerges

---
Pomodoro n°6: --- vim lisp syntax highlight

Found this plugin Plug 'luochen1990/rainbow'

Scratch that

I'm a bit disappointed that my workhorse vim-polyglot doesn't have syntax highlight for LISP.
It does for Clojure and Racket tho, so...

What I'm gonna miss is a REPL, but I'll deal with it later.

Let's try HiPhish/guile.vim

...Alright, that does the trick with `.scm` files

---
Pomodoro n°7 -- reading introduction of Little Schemer

up to the Law of Car.
> The primitive `car` is defined only for non-empty lists.

---
Pomodoro n° 8 -- reading foreword and prefaces of SICP

very interesting, I'll want to re-read those.
I liked the comparisons of LISP with Chess and can't wait to see it with my own eyes.



