LaTeX package 'storebox'
~~~~~~~~~~~~~~~~~~~~~~~~
Copyright (c) 2011-2022 by Martin Scharrer <martin.scharrer@web.de>  
License: LaTeX Project Public License, v1.3 or later: http://www.latex-project.org/lppl.txt  
Repository: https://github.com/MartinScharrer/storebox
Issues: https://github.com/MartinScharrer/storebox/issues 

This package provides "store boxes" which have the same user interface like normal LaTeX "save boxes", but only 
store the content once in the output file even if it is used several times.
At the moment only native PDF output is supported (i.e. pdflatex and lualatex).
If the stored content is not used in the document after all it is not written to the PDF (at least the pdftex manual says so).
For any other TeX and output format the package simply falls back to use the normal savebox equivalents.
