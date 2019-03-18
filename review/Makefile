.PHONY: all
all: review.pdf

FILES=		review.tex aims.tex literature.tex

review.pdf: ${FILES}


.PHONY: clean
clean:
	${RM} review.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
