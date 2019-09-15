## Makefile.am for gimp/data/images

imagedatadir = $(gimpdatadir)/images

if GIMP_UNSTABLE
GIMP_LOGO = gimp-devel-logo.png
else
GIMP_LOGO = icon_128.png
endif

imagedata_DATA = \
	$(GIMP_LOGO)	\
	glimpse-splash.png	\
	icon_256.png

EXTRA_DIST = $(imagedata_DATA)
