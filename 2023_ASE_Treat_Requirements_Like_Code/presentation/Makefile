presentation.pdf: presentation.tex pictures/schema.pdf
	-lualatex presentation.tex
	lualatex presentation.tex

pictures/schema.pdf: schema.tex
	pdflatex schema.tex
	pdftrimwhite schema.pdf
	mv pdftrimwhite.pdf pictures/schema.pdf
