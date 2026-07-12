LATEX = latexmk -pdf --shell-escape

default: camera_ready_fhn_fno.pdf

camera_ready_fhn_fno.pdf: Makefile *.tex *.bib figures/*.png
	$(LATEX) camera_ready_fhn_fno

clean:
	rm -f *-blx.bib *.4ct *.4og *.4tc *.aux *.bbl *.bcf *.blg *.doc *.dvi *.fdb_latexmk *.fls *.idv *.lg *.log *.nav *.odt *.out *.rtf *.snm *.tmp *.toc *.vrb *.xml *.xref $(outputs)
