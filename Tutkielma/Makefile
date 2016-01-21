all: kandidaatintutkielma.pdf

kandidaatintutkielma.pdf : *.tex *.sty content/*.tex
	latexmk -pdflatex="lualatex %O %S" -pdf -ps- -dvi- -recorder kandidaatintutkielma

clean:
	latexmk -C -silent
