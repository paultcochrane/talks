.PHONY: clean show view

PROJECT_NAME = waking-up-with-perl6
PDF = $(PROJECT_NAME).pdf
TEX = $(PROJECT_NAME).tex

$(PDF): $(TEX)
	pdflatex $<

show: view

view: $(PDF)
	evince $< & 2> /dev/null

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc $(PDF)
