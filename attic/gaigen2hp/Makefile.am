sandbindir = $(bindir)/ga_sandbox

sandbin_PROGRAMS = gaigen2hp

AM_CPPFLAGS = -I../.. $(AQSIS_FLTK_GL_CFLAGS)

gaigen2hp_LDADD = ../../libgasandbox/libgasandbox.a $(AQSIS_FLTK_GL_LIBS) $(OPENGL_LIBS)

gaigen2hp_SOURCES = gaigenhp_hpindex.cpp gaigenhp_fields.cpp  gaigenhp_glwindow.cpp  gaigenhp_main.cpp

noinst_HEADERS = fields.h  glwindow.h  hpindex.h  main.h

