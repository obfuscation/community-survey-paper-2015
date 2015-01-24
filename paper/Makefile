
latexfile = main
TEX = pdflatex
BIB = bibtex
TEXSOURCES = *.tex 
BIBSOURCES = *.bib

$(latexfile).pdf : $(TEXSOURCES)
	$(TEX) $(latexfile);

full : $(TEXSOURCES) $(BIBSOURCES)
	$(TEX) $(latexfile); $(BIB) $(latexfile); $(TEX) $(latexfile); $(TEX) $(latexfile)

all : $(latexfile).pdf

zip :
	zip obfuscation.zip *.tex *.bib Makefile figures/*.tex

clean :
	@rm -f *.aux *.bbl *.blg *.log *~ main.pdf figures/*~
