all: bib tex
	pdflatex article.tex
	evince article.pdf &

bib: article.bib
	pdflatex article.tex
	bibtex article

tex: article.tex
	pdflatex article.tex

clean:
	rm *.bbl *.aux *.blg *.log *.pdf
