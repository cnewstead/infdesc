An Infinite Descent into Pure Mathematics
=========================================

This Git repository contains the TeX source for _An Infinite Descent into Pure Mathematics_ by Clive Newstead.

The main website for the book is [here](https://infinitedescent.xyz/).

## Navigating the source

To compile the source, you will need a LaTeX implementation on your computer, or a browser-based LaTeX editor such as [Overleaf](https://www.overleaf.com/), using the compiler pdfLaTeX.

The root document is `book.tex`, which calls all the other files it needs to compile the document.

The `book` folder contains the bulk of the actual content of the book, and is fairly easy to navigate. For example, to find the source for Section 4.2 (_Equivalence relations_), navigate to `book/ch04-relations/s2-equivalence-relations.tex`.

The `book/includes` folder contains all the code used for calling packages, taking care of formatting, custom commands and environments, and so on.

## Modifications and adaptations

This TeX source is released under a [Creative Commons Attribution–ShareAlike 4.0 International licence](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0). Any derivatives must be released under the same licence, and must clearly attribute Clive Newstead as the creator of the original work on which the derivative is based.

To ensure compliance with the CC BY-SA 4.0 licence, if you want to modify or adapt the TeX source for your own use, please update the `\authorname` and `\authoremail` commands in the `book.tex` file with your name and email address, respectively. This will automatically attribute adaptations to you.
