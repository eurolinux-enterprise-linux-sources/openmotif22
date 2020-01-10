MAINTAINERCLEANFILES = Makefile.in

datadir = ${prefix}/share/Xm/DropDown

bin_PROGRAMS = dropdown
EXTRA_DIST = DropDown.ad Imakefile
dropdown_SOURCES = dropdown.c
data_DATA = $(EXTRA_DIST) $(dropdown_SOURCES)
TOPDIR = ../../..
LDADD = $(TOPDIR)/lib/Xm/libXm.la
INCLUDES = -I$(TOPDIR)/lib -I$(srcdir)/$(TOPDIR)/lib ${X_CFLAGS} 
