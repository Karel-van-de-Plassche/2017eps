.PHONY: main.pdf all clean lstpatch.sty

all: main.pdf

lstpatch.sty:

main.pdf: epspaper.tex
	latexmk -pdf -pdflatex="pdflatex -interaction=nonstopmode" -use-make $<

clean:
	latexmk -CA
