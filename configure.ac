AC_INIT([wayland-wsegl], [0.1], [carsten.munk@gmail.com])
AM_INIT_AUTOMAKE([1.11 foreign dist-bzip2])

AM_SILENT_RULES([yes])

AC_PROG_CC
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_HEADERS([config.h])

# Initialize libtool
LT_PREREQ([2.2])
LT_INIT([disable-static])

PKG_PROG_PKG_CONFIG()

PKG_CHECK_MODULES(WAYLAND,[wayland-server wayland-client])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
