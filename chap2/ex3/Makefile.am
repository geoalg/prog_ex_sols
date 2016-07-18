sandbindir = $(bindir)/ga_sandbox

sandbin_PROGRAMS = chap2ex3

AM_CPPFLAGS = -I../.. $(OPENGL_CFLAGS)

chap2ex3_LDADD = ../../libgasandbox/libgasandbox.a $(OPENGL_LIBS) $(GLUT_LIBS)

chap2ex3_SOURCES = hpindex.cpp fields.cpp  main.cpp render.cpp

noinst_HEADERS = fields.h  hpindex.h  main.h render.h

