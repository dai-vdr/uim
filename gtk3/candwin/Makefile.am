if GTK3
libexec_PROGRAMS = uim-candwin-gtk3 uim-candwin-tbl-gtk3 uim-candwin-horizontal-gtk3
uim_candwin_gtk3_SOURCES  = ../../gtk2/candwin/gtk.c \
			   ../../gtk2/immodule/caret-state-indicator.c \
			   ../../gtk2/immodule/caret-state-indicator.h
uim_candwin_gtk3_LDADD    = @GTK3_LIBS@ $(top_builddir)/uim/libuim-scm.la \
			   $(top_builddir)/uim/libuim.la
uim_candwin_gtk3_CPPFLAGS = -I$(top_srcdir)
uim_candwin_gtk3_CFLAGS   = @GTK3_CFLAGS@

uim_candwin_tbl_gtk3_SOURCES  = ../../gtk2/candwin/tbl-gtk.c \
			   ../../gtk2/immodule/caret-state-indicator.c \
			   ../../gtk2/immodule/caret-state-indicator.h
uim_candwin_tbl_gtk3_LDADD    = @GTK3_LIBS@ $(top_builddir)/uim/libuim-scm.la \
			   $(top_builddir)/uim/libuim.la
uim_candwin_tbl_gtk3_CPPFLAGS = -I$(top_srcdir)
uim_candwin_tbl_gtk3_CFLAGS   = @GTK3_CFLAGS@

uim_candwin_horizontal_gtk3_SOURCES  = ../../gtk2/candwin/horizontal-gtk.c \
			   ../../gtk2/immodule/caret-state-indicator.c \
			   ../../gtk2/immodule/caret-state-indicator.h
uim_candwin_horizontal_gtk3_LDADD    = @GTK3_LIBS@ $(top_builddir)/uim/libuim-scm.la \
			   $(top_builddir)/uim/libuim.la
uim_candwin_horizontal_gtk3_CPPFLAGS = -I$(top_srcdir)
uim_candwin_horizontal_gtk3_CFLAGS   = @GTK3_CFLAGS@
endif
