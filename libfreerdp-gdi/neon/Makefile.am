## Process this file with automake to produce Makefile.in

# libfreerdp-gdi-neon
noinst_LTLIBRARIES = libfreerdp-gdi-neon.la

libfreerdp_gdi_neon_la_SOURCES =

if WITH_NEON
libfreerdp_gdi_neon_la_SOURCES += \
	gdi_neon.c gdi_neon.h
endif

libfreerdp_gdi_neon_la_CFLAGS = \
	-I$(top_srcdir) \
	-I$(top_srcdir)/include \
	-I..

libfreerdp_gdi_neon_la_LDFLAGS =

libfreerdp_gdi_neon_la_LIBDADD =

# extra
EXTRA_DIST =

DISTCLEANFILES = 
