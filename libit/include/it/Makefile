# Makefile.in generated automatically by automake 1.4-p6 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999, 2001 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.

# The directory where the include files will be installed


SHELL = /bin/bash

srcdir = .
top_srcdir = ../..

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

top_builddir = ../..

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

libitincludedir = $(includedir)/it

# Which header files to install
libitinclude_HEADERS = \
	arithmetic_codec.h      \
	channel.h      \
	convcode.h     \
	cplx.h         \
	distance.h     \
	fastica.h      \
	filter.h       \
	fourier.h      \
	hlist.h        \
	hmmalgo.h      \
	interleaver.h  \
	io.h           \
	linalg.h       \
	mat.h          \
	math.h 	       \
	parser.h       \
	poly.h         \
	quantizer.h    \
	random.h       \
	source.h       \
	source_fit.h   \
	source_func.h  \
	transform.h    \
	transform2D.h  \
	separable2D.h  \
	types.h        \
	vec.h          \
	vlc.h          \
	wavelet.h      \
	wavelet2D.h

mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_CLEAN_FILES = 
HEADERS =  $(libitinclude_HEADERS)

DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
all: all-redirect
.SUFFIXES:
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --gnu include/it/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status $(BUILT_SOURCES)
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


install-libitincludeHEADERS: $(libitinclude_HEADERS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(libitincludedir)
	@list='$(libitinclude_HEADERS)'; for p in $$list; do \
	  if test -f "$$p"; then d= ; else d="$(srcdir)/"; fi; \
	  echo " $(INSTALL_DATA) $$d$$p $(DESTDIR)$(libitincludedir)/$$p"; \
	  $(INSTALL_DATA) $$d$$p $(DESTDIR)$(libitincludedir)/$$p; \
	done

uninstall-libitincludeHEADERS:
	@$(NORMAL_UNINSTALL)
	list='$(libitinclude_HEADERS)'; for p in $$list; do \
	  rm -f $(DESTDIR)$(libitincludedir)/$$p; \
	done

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags $(ETAGS_ARGS) $$tags  $$unique $(LISP) -o $$here/TAGS)

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = include/it

distdir: $(DISTFILES)
	here=`cd $(top_builddir) && pwd`; \
	top_distdir=`cd $(top_distdir) && pwd`; \
	distdir=`cd $(distdir) && pwd`; \
	cd $(top_srcdir) \
	  && $(AUTOMAKE) --include-deps --build-dir=$$here --srcdir-name=$(top_srcdir) --output-dir=$$top_distdir --gnu include/it/Makefile
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

install-data-am: install-libitincludeHEADERS
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-libitincludeHEADERS
uninstall: uninstall-am
all-am: Makefile $(HEADERS)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(libitincludedir)


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-tags mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-tags clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-tags distclean-generic clean-am
	-rm -f libtool

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-tags maintainer-clean-generic \
		distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: uninstall-libitincludeHEADERS install-libitincludeHEADERS tags \
mostlyclean-tags distclean-tags clean-tags maintainer-clean-tags \
distdir info-am info dvi-am dvi check check-am installcheck-am \
installcheck install-exec-am install-exec install-data-am install-data \
install-am install uninstall-am uninstall all-redirect all-am all \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
