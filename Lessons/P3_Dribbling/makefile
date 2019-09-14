CC = pdflatex

SOURCE = P3_Dribbling.tex

FNAMES=$(join $( $(dir $(SOURCE))), $(notdir $(SOURCE:.tex=.tex))) 

PDFS=$(SOURCE:.tex=.pdf)

	
all: $(PDFS)
	@echo "Building: $(PDFS)"
	#cp -r $(PDFS) ../Release/$(PDFS)
	cp -r $(PDFS) ../Release/P4_Dribbling.pdf

clean:
	rm $(PDFS)
	rm *.aux
	rm *.log

%.pdf : %.tex
	 @$(CC) $<
