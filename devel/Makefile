.PHONY: all
all: devel.pdf devel-slides.pdf

SRC+=		preamble.tex
SRC+=		abstract.tex contents.tex

DEP+= 		bibsp.sty
DEP+= 		assessment.sty

devel.pdf: devel.tex
devel.pdf: ${SRC} ${DEP}

devel-slides.pdf: devel-slides.tex
devel-slides.pdf: ${SRC} ${DEP}


.PHONY: clean
clean:
	${RM} devel.pdf devel-slides.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk

INCLUDE_BIBSP=../bibsp
include ${INCLUDE_BIBSP}/bibsp.mk

INCLUDE_BIBEDU=../bibedu
include ${INCLUDE_BIBEDU}/bibedu.mk
