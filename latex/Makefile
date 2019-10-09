MAIN := paper.tex
LTEX := --latex-args="-shell-escape"
BTEX := --bibtex-args="-min-crossrefs=99"

.PHONY: FORCE
paper.pdf: FORCE
	@TEXINPUTS="sty:" python3 ./latexrun.py $(LTEX) $(BTEX) $(MAIN)

.PHONY: clean
clean:
	python3 ./latexrun.py --clean-all
