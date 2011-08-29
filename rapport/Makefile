DOC=rapport

full:
	pdflatex ${DOC}.tex; \
	bibtex ${DOC}.aux; \
	pdflatex ${DOC}.tex; \
	pdflatex ${DOC}.tex

light:
	pdflatex ${DOC}

clean:
	rm -rfv *.aux *.bbl *.blg *.lof *.log *.out *.toc
