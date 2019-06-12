# Autoconf requirements
# Initialize, but use more options. Note parameters brackets and whitespace.
AC_INIT([hello], [0.01], [dwheeler@dwheeler.com],
				[hello], [http://www.dwheeler.com])
#Force autoconf to be at least this version number:
AC_PREREQ([2.68])

#Safety Check - list a source file that wouldn't be in other directories:
AC_CONFIG_SRCDIR([hello.c])

# Put config results here, so we can easily #include them:
AC_CONFIG_HEADERS([config.h])

# Put autotools aux files in subdir to reduce clutter:
AC_CONFIG_AUX_DIR([Makefile])

# Look for a C compiler:
AC_PROG_CC

# Its possible to check for: more programs, libraries, header files, types, structures, compiler characteristics, library functions, system services.

# Final output
AC_OUTPUT
