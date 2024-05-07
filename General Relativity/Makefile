BOOK=tstextbook

all:
	pdflatex $(BOOK)

final:
	pdflatex $(BOOK)
	biber $(BOOK)
	makeindex $(BOOK)
	pdflatex $(BOOK)
	pdflatex $(BOOK)

clean:
	rm -f *.aux *.mtc* *.out *.idx *.bcf *.log *~ *.ptc *.toc *.run.xml *.maf *.bbl *.fdb_latexmk *.fls *.ilg *.ind *.gz *.xdv
