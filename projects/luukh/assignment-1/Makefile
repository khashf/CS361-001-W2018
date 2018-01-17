TARGET=vision

default: pdf

pdf: ${TARGET}.tex
	pdflatex ${TARGET}.tex
	bibtex ${TARGET}
	pdflatex ${TARGET}.tex
	pdflatex ${TARGET}.tex

clean:
	rm -f *.aux
	rm -f *.log
	rm -f *.dvi
	rm -f *.toc
	rm -f *.ps
	rm -f *.bbl
	rm -f *.blg
	rm -f ${TARGET}.pdf
