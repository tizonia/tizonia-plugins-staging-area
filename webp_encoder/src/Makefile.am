# Copyright (C) 2011-2014 Aratelia Limited - Juan A. Rubio
#
# This file is part of Tizonia
#
# Tizonia is free software: you can redistribute it and/or modify it under the
# terms of the GNU Lesser General Public License as published by the Free
# Software Foundation, either version 3 of the License, or (at your option)
# any later version.
#
# Tizonia is distributed in the hope that it will be useful, but WITHOUT ANY
# WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE.  See the GNU Lesser General Public License for
# more details.
#
# You should have received a copy of the GNU Lesser General Public License
# along with Tizonia.  If not, see <http://www.gnu.org/licenses/>.

lib_LTLIBRARIES = libtizwebpe.la

noinst_HEADERS = \
	webpeprc.h \
	webpeprc_decls.h

libtizwebpe_la_SOURCES = \
	webpe.c \
	webpeprc.c

libtizwebpe_la_CFLAGS = \
	-I$(top_srcdir)/../../include/omxil-1.2 \
	-I$(top_srcdir)/../../libtizplatform/src \
	-I$(top_srcdir)/../../libtizonia/src

libtizwebpe_la_LIBADD = \
	$(top_builddir)/../../libtizplatform/src/libtizplatform.la \
	$(top_builddir)/../../libtizonia/src/libtizonia.la


