lib_LTLIBRARIES = libXxf86vm.la

libXxf86vm_la_SOURCES = XF86VMode.c

AM_CFLAGS = $(BASE_CFLAGS) $(XXF86VM_CFLAGS) $(MALLOC_ZERO_CFLAGS)
AM_CPPFLAGS = -I$(top_srcdir)/include

libXxf86vm_la_LIBADD = $(XXF86VM_LIBS)
libXxf86vm_la_LDFLAGS = -version-number 1:0:0

libXxf86vmincludedir = $(includedir)/X11/extensions
libXxf86vminclude_HEADERS = $(top_srcdir)/include/X11/extensions/xf86vmode.h
