# Makefile.in generated automatically by automake 1.4-p6 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# This is partially taken from the Linux kernel Documentation

# The directory where to install the documentation


SHELL = /bin/bash

srcdir = .
top_srcdir = ..

prefix = /user/1/comothh/Documents/MULTIMEDIA/runtime
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/share/info
mandir = ${prefix}/share/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/libit
pkglibdir = $(libdir)/libit
pkgincludedir = $(includedir)/libit

top_builddir = ..

ACLOCAL = /user/1/comothh/Documents/MULTIMEDIA/libit/missing aclocal-1.4
AUTOCONF = autoconf
AUTOMAKE = /user/1/comothh/Documents/MULTIMEDIA/libit/missing automake-1.4
AUTOHEADER = autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL}
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
host_alias = 
host_triplet = x86_64-unknown-linux-gnu
AS = @AS@
BINARY_AGE = 0
CC = gcc
DLLTOOL = @DLLTOOL@
INTERFACE_AGE = 0
IT_RLD_FLAGS = -Wl,-rpath,${exec_prefix}/lib
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
LT_AGE = 0
LT_CURRENT = 3
LT_RELEASE = 0.2
LT_REVISION = 0
MAJOR_VERSION = 0
MAKEINFO = /user/1/comothh/Documents/MULTIMEDIA/libit/missing makeinfo
MICRO_VERSION = 3
MINOR_VERSION = 2
OBJDUMP = @OBJDUMP@
PACKAGE = libit
RANLIB = ranlib
VERSION = 0.2.3

docdir = ${prefix}/doc/$(PACKAGE)

# Include these in the distribution
EXTRA_DIST = *.sgml libit.pdf libit.ps

# What files we depend on
BOOKS = libit.tex intro.tex vecmat.tex io.tex measure.tex objects.tex source.tex channel.tex signal.tex manpages.sgml

# The tools for building the documentation
SGMLTOOLS = jw
TEX = latex
DVIPS = dvips
CONVERT = convert
MV = mv
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_CLEAN_FILES = 
DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
all: all-redirect
.SUFFIXES:
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu doc/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status $(BUILT_SOURCES)
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status

tags: TAGS
TAGS:


distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = doc

distdir: $(DISTFILES)
	here=`cd $(top_builddir) && pwd`; \
	top_distdir=`cd $(top_distdir) && pwd`; \
	distdir=`cd $(distdir) && pwd`; \
	cd $(top_srcdir) \
	  && $(AUTOMAKE) --include-deps --build-dir=$$here --srcdir-name=$(top_srcdir) --output-dir=$$top_distdir --gnu doc/Makefile
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	$(MAKE) $(AM_MAKEFLAGS) top_distdir="$(top_distdir)" distdir="$(distdir)" dist-hook
info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am:
install-exec: install-exec-am

install-data-am:
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) install-data-hook
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am:
uninstall: uninstall-am
all-am: Makefile
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-generic clean-am
	-rm -f libtool

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-generic distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: tags distdir info-am info dvi-am dvi check check-am \
installcheck-am installcheck install-exec-am install-exec \
install-data-am install-data install-am install uninstall-am uninstall \
all-redirect all-am all installdirs mostlyclean-generic \
distclean-generic clean-generic maintainer-clean-generic clean \
mostlyclean distclean maintainer-clean


book: libit.pdf libit.ps

libit.ps: $(BOOKS) 
	latex libit.tex
	dvips -o libit.ps libit.dvi

libit.pdf: $(BOOKS) 
	pdflatex libit.tex

man: $(BOOKS)
	$(SGMLTOOLS) -d libit.dsl\#print -o man3 -b man libit.sgml

html: $(BOOKS)
	$(SGMLTOOLS) -d libit.dsl\#html -o html -b html libit.sgml

eq-%.dvi: eq-%.tex
	$(TEX) $< -o $<

eq-%.eps: eq-%.dvi
	$(DVIPS) -E $< -o $@

eq-%.pdf: eq-%.eps
	$(EPSTOPDF) $<

eq-%.png: eq-%.eps
	$(CONVERT) -density 150 $< $@
# this is actually needed in the html directory
	$(MV) $@ html/

# Install the HTML pages in the documentation directory
install-data-hook:
	$(mkinstalldirs) $(docdir) $(mandir)/man3
	$(INSTALL) html/*.html html/*.png $(docdir)
	$(INSTALL) man3/*.3 $(mandir)/man3

###
# Temporary files left by various tools
dist-clean:
	$(RM) *.dvi *.aux *.tex *.log *.out *.ps *.pdf *.html *.3
	$(RM) -r html

# Grab the HTML manual for the distribution:
dist-hook:
	cp -rp html $(distdir)
	cp -rp man3 $(distdir)

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
