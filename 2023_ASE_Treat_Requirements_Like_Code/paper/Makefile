paper.pdf: paper.tex paper.bib
	-lualatex --draftmode --interaction=batchmode paper.tex
	bibtex paper.aux
	-lualatex --interaction=batchmode paper.tex
	lualatex --file-line-error --halt-on-error --interaction=errorstopmode paper.tex
