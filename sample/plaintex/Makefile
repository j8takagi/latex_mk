TEXMAIN := *
TEXTARGETS := $(subst .tex,.pdf,$(wildcard $(TEXMAIN).tex))

.PHONY: all clean distclean

all: $(TEXTARGETS)

include tex.mk

TEX := tex

clean: tex-clean

distclean: clean tex-distclean
