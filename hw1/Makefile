write-up.pdf : write-up.ps
	ps2pdf write-up.ps
	rm write-up.ps write-up.dvi write-up.log write-up.aux
write-up.dvi : write-up.tex
	latex write-up.tex
write-up.ps : write-up.dvi 
	dvips write-up.dvi
