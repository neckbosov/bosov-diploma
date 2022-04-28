MAIN=thesis-main

all:
	latexmk -bibtex -pdf -ps- -dvi- -recorder -shell-escape -interaction=nonstopmode $(MAIN).tex

clean:
	latexmk -c
	rm -f *.snm *.nav *.vrb *.synctex.gz *.bbl *.log
	rm -rf _minted-*

FORCE:
