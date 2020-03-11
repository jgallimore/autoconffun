AC_INIT([amhello], [1.0], [bug-automake@gnu.org])
AC_PROG_CC
AC_CHECK_HEADERS(zlib.h)
AC_SEARCH_LIBS(deflate, z)
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
 Makefile
 src/Makefile
])
AC_OUTPUT

