PDFLATEX = pdflatex -halt-on-error -file-line-error
FILENAME = vernier

all:
	$(PDFLATEX) $(FILENAME).tex
	$(PDFLATEX) $(FILENAME).tex
	bibtex $(FILENAME)
	$(PDFLATEX) $(FILENAME).tex
	$(PDFLATEX) $(FILENAME).tex
