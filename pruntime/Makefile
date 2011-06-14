all: source.pdf
source.pdf: source.tex related.tex
	pdflatex source.tex
	bibtex source.aux
	pdflatex source.tex
	pdflatex source.tex
clean:
	rm *.log *.aux *.out source.pdf
