MAIN=thesis-main

all:
	latexmk -pdf -ps- -dvi- -recorder -shell-escape -interaction=nonstopmode $(MAIN).tex
	cp ${MAIN}.pdf st069504.pdf
clean:
	latexmk -c
	rm -f *.snm *.nav *.vrb *.synctex.gz *.bbl *.log *.aux */*.aux *.run.xml
	rm -rf _minted-*

FORCE:
