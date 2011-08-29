DOC=rapport

all:
	pdflatex ${DOC}.tex; \
	bibtex ${DOC}.aux; \
	pdflatex ${DOC}.tex; \
	pdflatex ${DOC}.tex

tex:
	pdflatex ${DOC}

bib:
	bibtex ${DOC}.aux

clean:
	rm -rfv *.aux *.bbl *.blg *.lof *.log *.out *.toc
