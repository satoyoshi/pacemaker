#
# Copyright (C) 2004 Andrew Beekhof
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# as published by the Free Software Foundation; either version 2
# of the License, or (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.
#
MAINTAINERCLEANFILES    = Makefile.in

INCLUDES        = -I$(top_builddir)/include  -I$(top_srcdir)/include  \
		  -I$(top_builddir)/libltdl  -I$(top_srcdir)/libltdl

## libraries
lib_LTLIBRARIES	= libtransitioner.la

## SOURCES
noinst_HEADERS		= 
libtransitioner_la_SOURCES	= unpack.c graph.c utils.c

libtransitioner_la_LDFLAGS	= -version-info 2:0:0
libtransitioner_la_CFLAGS	= -I$(top_builddir)

clean-generic:
	rm -f *~

install-exec-local:

uninstall-local:
