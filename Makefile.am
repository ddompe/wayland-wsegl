ACLOCAL_AMFLAGS = -I m4

lib_LTLIBRARIES = libwayland-egl.la

libwayland_egl_la_SOURCES = waylandwsegl.c wayland-drm-protocol.c
noinst_HEADERS = wsegl.h wayland-egl-priv.h wayland-drm-client-protocol.h
libwayland_egl_la_LIBADD = -lpvr2d $(WAYLAND_LDFLAGS) 
libwayland_egl_la_LDFLAGS= -version-info 1:0:0

