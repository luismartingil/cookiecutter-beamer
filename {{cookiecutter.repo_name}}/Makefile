all:
	pdflatex -shell-escape main.tex
	pdflatex -shell-escape main.tex # doing twice for the toc file...
clean:
	find . -type f -name "*.vrb" -exec rm -f '{}' \;
	find . -type f -name "*.out" -exec rm -f '{}' \;
	find . -type f -name "*.snm" -exec rm -f '{}' \;
	find . -type f -name "*.mtc*" -exec rm -f '{}' \;
	find . -type f -name "*.toc" -exec rm -f '{}' \;
	find . -type f -name "*.aux" -exec rm -f '{}' \;
	find . -type f -name "*.log" -exec rm -f '{}' \;
	find . -type f -name "*.maf" -exec rm -f '{}' \;
	find . -type f -name "*.nav" -exec rm -f '{}' \;
	find . -type f -name "*.pyg" -exec rm -f '{}' \;
	find . -type f -name "*~" -exec rm -f '{}' \;