AC_INIT([arc-firefox-theme], [45.20160308], [https://github.com/horst3180/arc-firefox-theme/issues], [arc-palemoon-theme], [https://github.com/horst3180/arc-firefox-theme])
AM_INIT_AUTOMAKE([-Wno-portability no-dist-gzip dist-xz foreign subdir-objects tar-ustar])
AC_PREFIX_DEFAULT(/usr/local)
AM_SILENT_RULES([yes])
AC_CONFIG_MACRO_DIR([m4])
AC_PROG_MKDIR_P


ARC_ENABLE([LIGHT],         [light],         [Arc Light Pale Moon],     [disable])
ARC_ENABLE([DARKER],        [darker],        [Arc Darker Pale Moon],    [disable])
ARC_ENABLE([DARK],          [dark],          [Arc Dark Pale Moon],      [disable])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT

AC_MSG_RESULT([
        arc-palemoon-theme $VERSION
        ========

        prefix:                 ${prefix}
        exec_prefix:            ${exec_prefix}
        datarootdir:            ${datarootdir}
])
