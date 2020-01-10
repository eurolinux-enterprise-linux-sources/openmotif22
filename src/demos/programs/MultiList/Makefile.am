MAINTAINERCLEANFILES = Makefile.in

datadir = ${prefix}/share/Xm/MultiList

bin_PROGRAMS = multilist
SUBDIRS = pixmaps
multilist_SOURCES = bxutil-c.c callbacks-c.c creation.c multilist.c \
         extlist.h
EXTRA_DIST = Imakefile
data_DATA = $(EXTRA_DIST) $(multilist_SOURCES)
TOPDIR = ../../..
LDADD = $(TOPDIR)/lib/Xm/libXm.la

INCLUDES = -I$(TOPDIR)/lib -I.. -I$(srcdir)/$(TOPDIR)/lib ${X_CFLAGS} 
