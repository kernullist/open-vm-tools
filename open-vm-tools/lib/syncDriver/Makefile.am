################################################################################
### Copyright (C) 2007-2015 VMware, Inc.  All rights reserved.
###
### This program is free software; you can redistribute it and/or modify
### it under the terms of version 2 of the GNU General Public License as
### published by the Free Software Foundation.
###
### This program is distributed in the hope that it will be useful,
### but WITHOUT ANY WARRANTY; without even the implied warranty of
### MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
### GNU General Public License for more details.
###
### You should have received a copy of the GNU General Public License
### along with this program; if not, write to the Free Software
### Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
################################################################################

noinst_LTLIBRARIES = libSyncDriver.la

libSyncDriver_la_SOURCES =
libSyncDriver_la_SOURCES += syncDriverPosix.c

if LINUX
   libSyncDriver_la_SOURCES += nullDriver.c
   libSyncDriver_la_SOURCES += syncDriverLinux.c
   libSyncDriver_la_SOURCES += vmSyncDriver.c
endif

