AC_INIT([SPP], 1.7)
AC_CHECK_LIB(bz2, BZ2_bzDecompressInit)
AC_SUBST(HAVE_LIBBZ2)
BOOST_REQUIRE([1.41.0])
BOOST_CPPFLAGS="${BOOST_CPPFLAGS}"
AC_SUBST(BOOST_CPPFLAGS)
AC_CONFIG_FILES([src/Makevars])
cp confdefs.h src/config.h
AC_OUTPUT
