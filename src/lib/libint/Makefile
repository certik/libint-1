TOPDIR=../../..
TO_TOPDIR=$(TOPDIR)
ifndef SRCDIR
  SRCDIR=$(shell pwd)
endif
TOPOBJDIR = $(shell ls -d `pwd`/$(TOPDIR))

NAME = libint
VERSION = 2
TARGET = $(NAME)$(VERSION).$(LIBSUF)
COMPILER = build_$(NAME)

-include $(TOPDIR)/src/lib/MakeVars
-include $(TOPDIR)/src/lib/MakeRules
include $(SRCDIR)/$(TOPDIR)/lib/MakeRules
include $(SRCDIR)/$(TOPDIR)/lib/MakeSuffixRules
