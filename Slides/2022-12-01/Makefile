
DOCO := Hazen_elx_mfg
PDF := ${DOCO}.pdf
TEX := ${DOCO}.tex
FIGS := figs/*

all: ${PDF}

${PDF}: ${TEX} ${FIGS}
	pdflatex ${TEX}
	pdflatex ${TEX}

clean:
	rm -f *.aux *.nav *.out *.snm *.toc *.log *~ \#*


