SUBDIRS = src doc model include test swig

EXTRA_DIST = \
	LICENSE \
	autogen.sh \
	m4/pkg.m4 \
	pocketsphinx.pc.in \
	pocketsphinx.sln

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = pocketsphinx-CocoaPod.pc
CLEANFILES = pocketsphinx-CocoaPod.pc

ACLOCAL_AMFLAGS = -I m4
