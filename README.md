latex-beamer-default
====================

Default draft for a latex beamer representation with some special commands like framepicture{}

Standalone
--------------------
   
    git clone git@github.com:orthez/latex-beamer-default.git beamer
    cp beamer/default-draft.tex . && pdflatex default-draft.tex

    
Embedding in already existing project
--------------------

    git submodule add git@github.com:orthez/latex-beamer-default.git beamer

In your latex file you can now add

    \input{beamer/util-beamer.tex}
