MiniClass.pdf:	MiniClass.tex Makefile biblio.bib
	pdflatex MiniClass.tex
	bibtex   MiniClass
	pdflatex MiniClass.tex
	pdflatex MiniClass.tex


clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.toc