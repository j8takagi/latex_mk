TEXMAIN := *
TEXTARGETS := $(subst .tex,.pdf,$(wildcard $(TEXMAIN).tex))

all: $(TEXTARGETS)

include tex.mk

clean: tex-clean

distclean: clean tex-distclean
