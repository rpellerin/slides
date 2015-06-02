all: slides.html

slides.html: style.html
	pandoc -t dzslides \
		--self-contained \
		--include-in-header=../style.html \
		-s slides.md \
		-o slides.html

slides.pdf: slides.tex
	pdflatex slides.tex

slides.tex: slides.md
	pandoc -t beamer \
		-s slides.md \
		-o slides.tex
