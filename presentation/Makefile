TEXFILES:=$(wildcard *.tex)
ROOT:=presentation
ROOT2:=presentation2

all: $(ROOT) $(ROOT2)

$(ROOT): $(TEXFILES)
	pdflatex $(ROOT)
	bibtex $(ROOT)
	pdflatex $(ROOT)
	
$(ROOT2): $(TEXFILES)
	pdflatex $(ROOT2)
	bibtex $(ROOT2)
	pdflatex $(ROOT2)

