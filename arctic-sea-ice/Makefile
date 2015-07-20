.PHONY: clean

PROJECT_NAME = arctic_sea_ice
PDF = $(PROJECT_NAME).pdf
TEX = $(PROJECT_NAME).tex

$(PDF): $(TEX)
	pdflatex $<

view: $(PDF)
	evince $< & 2> /dev/null

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc $(PDF)
