+++
title = "Emacs Should Be Emacs Lisp - Tom Tromey"
author = ["Jethro Kuan"]
lastmod = 2020-03-08T00:38:55+08:00
slug = "emacs_should_be_emacs_lisp"
draft = false
+++

talk
: <https://ftp.fau.de/fosdem/2020/UD2.119/emacsthoughts.webm>

speaker
: [Tom Tromey]({{< relref "20200213215019" >}})

tags
: [Emacs]({{< relref "emacs" >}}), [Emacs Lisp]({{< relref "emacs_lisp" >}})


## Several competing ideas and their problems {#several-competing-ideas-and-their-problems}

-   Guile Emacs
    -   Scheme is not Emacs Lisp! Impedance mismatch -- largely solved by
        Guile Scheme, at the expense of Guile not being a proper Scheme
    -   Scripting fragmentation (rather than have)
-   Rebase on Common Lisp
    -   Experiment in 2012, an attempt to unify the type systems
    -   Impedance mismatch, hard to maintain


## Emacs Should Be Emacs Lisp! {#emacs-should-be-emacs-lisp}

-   Easier to hack
-   Threads
-   GC
-   Library-only
-   FFI - [tromey/emacs-ffi](http://github.com/tromey/emacs-ffi)
