ACLOCAL_AMFLAGS = -I m4

lib_LTLIBRARIES = libwayland-egl.la waylandwsegl.la

libwayland_egl_la_SOURCES = wayland-egl.c
libwayland_egl_la_LIBADD = $(WAYLAND_LDFLAGS) 
libwayland_egl_la_LDFLAGS= -version-info 1:0:0

waylandwsegl_la_SOURCES = waylandwsegl.c wayland-drm-protocol.c
waylandwsegl_la_LIBADD = -lpvr2d $(WAYLAND_LDFLAGS) 
waylandwsegl_la_LDFLAGS= -module -avoid-version

noinst_HEADERS = wsegl.h wayland-egl-priv.h wayland-drm-client-protocol.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = wayland-egl.pc

EXTRA_DIST = wayland-egl.pc.in



