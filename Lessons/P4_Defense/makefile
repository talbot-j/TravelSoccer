CC = pdflatex

SOURCE = P4_Iron_Curtain_Defense.tex

FNAMES=$(join $( $(dir $(SOURCE))), $(notdir $(SOURCE:.tex=.tex))) 

PDFS=$(SOURCE:.tex=.pdf)

	
all: $(PDFS)
	@echo "Building: $(PDFS)"
	#cp -r $(PDFS) ../Release/$(PDFS)
	cp -r $(PDFS) ../Release/P3_Iron_Curtain_Defense.pdf
	
clean:
	rm $(PDFS)
	rm *.aux
	rm *.log

%.pdf : %.tex
	 @$(CC) $<
