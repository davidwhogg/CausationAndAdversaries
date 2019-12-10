.SUFFIXES: .tex .pdf
RM = /bin/rm -fv
PDFLATEX = pdflatex

all: hogg_causal_structure.pdf

%.pdf: %.tex hogg_presentation.tex
	$(PDFLATEX) $*

clean:
	$(RM) *.log *.aux *.dvi *.bbl *.blg
