INFILE=main.tex
LATEX=pdflatex

all:
	$(LATEX) $(INFILE)
	bibtex $(INFILE:.tex=.aux)
	$(LATEX) $(INFILE)

clean:
	rm -f *.pdf *.out *aux *bbl *blg *log *toc *.ptb *.tod *.fls *.fdb_latexmk *.lof