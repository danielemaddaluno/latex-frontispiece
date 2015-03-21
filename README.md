# Latex Frontispiece
Provides latex code to generate a simple frontispiece.<br\>
I will create for you a pdf frontispiece like this one:

![Screenshot](https://raw.githubusercontent.com/danielemaddaluno/latex-frontispiece/master/README-frontispiece.png)

Once produced the pdf frontispiece with this tex you can add it as first page of your tex following these two steps:
* add `\usepackage{pdfpages}` beetween the imports of your document.tex
* add `\includepdf[pages={1}]{frontispiece.pdf}` after your \begin{document}
