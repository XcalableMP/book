# Makefile for macAir:~/Project/XMPBook/book/chap3/

main.pdf : main.dvi
	dvipdfmx main.dvi

main.dvi : clean
	platex main
	platex main
	platex main

clean:
	rm -f  *~ *.aux *.log *.idx *.ind *.ilg *.lot *.lof *.toc *.dvi *.ps *.thm

clean-all : clean
	rm -f *.pdf

