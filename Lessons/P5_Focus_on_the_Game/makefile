CC = pdflatex

SOURCE = P5_Focus_on_the_Game.tex

FNAMES=$(join $( $(dir $(SOURCE))), $(notdir $(SOURCE:.tex=.tex))) 

PDFS=$(SOURCE:.tex=.pdf)

	
all: $(PDFS)
	@echo "Building: $(PDFS)"
	cp -r $(PDFS) ../Release/$(PDFS)

clean:
	rm $(PDFS)
	rm *.aux
	rm *.log

%.pdf : %.tex
	 @$(CC) $<
