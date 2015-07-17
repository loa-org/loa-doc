
main.pdf: main.tex content/intro.tex  content/styleguide.tex  content/titlepage.tex  content/toolchain.tex  content/version_control_system.tex
	xelatex -shell-escape main.tex 


view: main.pdf
	xdg-open main.pdf 

clean:
	rm -rf *.pdf *.aux  *.log  *.out *.pyg

all: main.pdf
