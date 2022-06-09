all: ms.pdf

%.pdf: %.tex
	tectonic ms.tex
	#cp ms.tex final
	rm -rf *Notes.bib
	rm -rf *.log
	rm -rf *.bbl
	rm -rf *.aux
	rm -rf *.out
	rm -rf *.blg
	rm -rf *.fdb_latexmk
	rm -rf *.dvi
	rm -rf *.fls
	rm -rf *.synctex.gz
	mv ms.pdf final/
	open final/ms.pdf
