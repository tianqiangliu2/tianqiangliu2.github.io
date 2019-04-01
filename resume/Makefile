NAME=resume

tryit: $(NAME).pdf
	open $(NAME).pdf

$(NAME).pdf: $(NAME).tex Makefile
	pdflatex $(NAME)
	cp $(NAME).pdf ../

clean:
	rm -f $(NAME).pdf $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).aux $(NAME).out *~




