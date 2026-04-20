all: svg

pdf:
	pdflatex asix_logo

svg: pdf
	pdf2svg asix_logo.pdf asix_logo.svg

copy:
	cp asix_logo.svg ../../docs/assets/images/asix_logo.svg

clean:
	rm -f asix_logo.aux asix_logo.log asix_logo.pdf asix_logo.svg