PDFLATEX:="pdflatex"

.PHONY: all

# all: 8up-zine-print-final.pdf
all: modelling-computation-as-tensors-print.pdf

%.pdf: %.tex
	$(PDFLATEX) $<

clean:
	rm -f *.pdf

modelling-computation-as-tensors-print.pdf: modelling-computation-as-tensors-step1.pdf
modelling-computation-as-tensors-step1.pdf: modelling-computation-as-tensors.pdf
# 8up-zine-print-final.pdf: 8up-zine-print-step1.pdf
# 8up-zine-print-step1.pdf: 8up-zine.pdf
