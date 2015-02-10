LaTeX_tutorial
==============

A beginner's guide to using LaTeX, including PSfrag
UH'ers: You can email me for examplefig1.eps and examplefig2.eps

mydocument.tex is a long document with several sections addressing aspects of LaTeX with verbatim sections that 
show markup in the text when built.

whylatex.tex is a very short document showing basic functionality.

To build latex documents with a bibliography in a separate .bib file from the command line, build the document, build the bibliography (using your document's name, not the .bib file's name), and the build your document twice more to get crossreferences correct:
latex mydocument
bibtex mydocument
latex mydocument
latex mydocument

Do not use file suffixes (i.e., .tex). Any files you need, such as images, should be in the same folder or their name in the .tex document should include a full path.
