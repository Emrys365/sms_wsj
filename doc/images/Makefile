all: example_id.svg room.svg

example_id.svg: example_id.tex
	pdflatex --shell-escape example_id.tex

room.svg: room.tex
	pdflatex --shell-escape room.tex

clean:
	rm -f example_id.fls
	rm -f example_id.log
	rm -f example_id.svg
	rm -f example_id.pdf
	rm -f example_id.blg
	rm -f example_id.fdb_latexmk
	rm -f example_id.aux
	rm -f example_id.bbl
