filename=tcc

tcc:
	pdflatex ${filename}.tex
	bibtex	${filename}
	pdflatex ${filename}.tex
	pdflatex ${filename}.tex

clean:
	rm -rf ${filename}.ps
	rm -rf ${filename}.pdf
	rm -rf ${filename}.log
	rm -rf ${filename}.aux
	rm -rf ${filename}.out
	rm -rf ${filename}.dvi
	rm -rf ${filename}.bbl
	rm -rf ${filename}.blg
	rm -rf ${filename}.lot
	rm -rf ${filename}.lof
	rm -rf ${filename}.toc
	rm -rf ${filename}.brf
	rm -rf ${filename}.out.ps
	rm -rf referencias.bib.aux
	rm -rf references.bib.bak
	rm -rf references.bib.aux
	rm -rf references.bib.bbl
	rm -rf references.bib.blg
