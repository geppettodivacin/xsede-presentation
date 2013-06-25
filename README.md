xsede-presentation
==================

Beamer theme for XSEDE slide presentations. Clone or extract to ~/texmf/tex/latex/beamer/themes/xsede. To use, add this to your preamble:

    \usetheme{xsede}

Bugs
----

To add a title page, you must use 

    \maketitle

and not 

    \frame{\titlepage{}}

due to the implementation of the title. Otherwise, there will be no background, date, or logo on the title page.

The institution is in an awkward place by default, and it is difficult to move it. For now, it would probably be better to include any institutions with the author like this:

    \author{First Last\\Institution}
