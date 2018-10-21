AUTOMAKE_OPTIONS=subdir-objects
ACLOCAL_AMFLAGS=$(ACLOCAL_FLAGS)
 
bin_PROGRAMS=ledbadge
ledbadge_SOURCES=main.c arg.c
ledbadge_CPPFLAGS = $(PNG_CFLAGS)
ledbadge_LDFLAGS= $(PNG_LIBS) -lledbadge

