## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src 

linjapdocdir = ${prefix}/doc/linjap
linjapdoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(linjapdoc_DATA) \
	src/jping.png\
	src/kana.dict


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(linjapdocdir)
