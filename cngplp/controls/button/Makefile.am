noinst_LTLIBRARIES=libufr2button.la
libufr2button_la_SOURCES=button.c button.h

AM_CPPFLAGS=-I$(top_srcdir)/cngplpmod\
	 -I$(top_srcdir)\
         @PACKAGE_CFLAGS@\
         @GLADE_PACKAGE_CFLAGS@

AM_CFLAGS= -Wall -O2 -fPIC

libufr2button_la_LIBADD=@PACKAGE_LIBS@ @GLADE_PACKAGE_LIBS@
