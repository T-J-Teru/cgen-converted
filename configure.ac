dnl Process this file with autoconf to produce a configure script.
dnl
dnl   Copyright 2012 Free Software Foundation
dnl
dnl This file is free software; you can redistribute it and/or modify
dnl it under the terms of the GNU General Public License as published by
dnl the Free Software Foundation; either version 3 of the License, or
dnl (at your option) any later version.
dnl 
dnl This program is distributed in the hope that it will be useful,
dnl but WITHOUT ANY WARRANTY; without even the implied warranty of
dnl MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
dnl GNU General Public License for more details.
dnl 
dnl You should have received a copy of the GNU General Public License
dnl along with this program; see the file COPYING3.  If not see
dnl <http://www.gnu.org/licenses/>.
dnl

AC_PREREQ(2.59)
dnl The "50" is a generic indicator that we're between 1.1 and 1.2.
AC_INIT(cgen, 1.1.50)
AC_CONFIG_SRCDIR(read.scm)
AC_CANONICAL_SYSTEM
AM_INIT_AUTOMAKE

AC_PROG_INSTALL
AC_EXEEXT

# Set target cpu.
arch=${target_cpu}
AC_SUBST(arch)

AM_MAINTAINER_MODE

# See doc/Makefile.am.
AM_CONDITIONAL(GENINSRC_NEVER, false)

AC_OUTPUT([Makefile doc/Makefile testsuite/Makefile testsuite/test-utils.sh])
