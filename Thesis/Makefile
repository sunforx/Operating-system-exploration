fig=./fig/mem*.tex

thesis : thesis.tex
	#cd fig/ && latexmk mem*.tex && cd ..
	#latexmk $(fig) 
	latexmk thesis.tex
aim : thesis.tex
	cd fig/ && latexmk mem*.tex && cd ..
	latexmk thesis.tex
	latexmk -c
	cd fig/ && latexmk -c && cd ..
clean :	
	latexmk -c
	#cd fig/ && latexmk -c && cd ..
