main.pdf : main.dvi
	dvipdfmx main.dvi

main.dvi : clean
	platex main
	platex main
	platex main

clean:
	rm -f  *~ *.aux *.log *.idx *.ind *.ilg *.lot *.lof *.toc *.dvi *.ps 

clean-all : clean
	rm -f *.pdf

