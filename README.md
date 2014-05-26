latex-beamer-default
====================

Default draft for a latex beamer representation with some special commands like framepicture{}

Standalone
====================
   
    git clone https://github.com/orthez/latex-beamer-default.git

    pdflatex default-draft.tex

    
Embedding in already existing project
====================

    git submodule add https://github.com/orthez/latex-beamer-default.git

In your latex file you can now add

    \input{latex-beamer-default/util-beamer.tex}
