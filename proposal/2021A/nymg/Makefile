all: GemPhase1_US.pdf

%.pdf: %.tex
	tectonic GemPhase1_US.tex
	rm -rf *.log
	rm -rf *.bbl
	rm -rf *.blg
	mv GemPhase1_US.pdf final
