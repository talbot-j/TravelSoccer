CC = pdflatex

SOURCE = P1_Intro/P1_Introduction.tex P2_Perfect_Passing/P2_Perfect_Passing.tex P3_Dribbling/P3_Dribbling.tex

FNAMES=$(join $( $(dir $(SOURCE))), $(notdir $(SOURCE:.tex=.tex))) 

#PDFS=$(join $( $(dir $(SOURCE))), $(notdir $(SOURCE:.tex=.pdf))) 
PDFS=$(SOURCE:.tex=.pdf)


	#@$(CC) P1_Intro/P1_Introduction.tex
	#@$(CC) P2_Perfect_Passing/P2_Perfect_Passing.tex
	#@$(CC) P2_Perfect_Passing/P2_Perfect_Passing.tex
	#@$(CC) $(SOURCE)
	
all: $(PDFS)
	@echo "List of targets: $(PDFS)"
	@echo "List of names: $(FNAMES)"


%.pdf : %.tex
	 @$(CC) $<
