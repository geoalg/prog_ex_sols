sandbindir = $(bindir)/ga_sandbox

sandbin_PROGRAMS = chap10ex3

AM_CPPFLAGS = -I../.. $(OPENGL_CFLAGS)

chap10ex3_LDADD = ../../libgasandbox/libgasandboxparse.a ../../libgasandbox/libgasandbox.a \
	$(OPENGL_LIBS) $(GLUT_LIBS) \
	-lopencv_core  $(ANTLR_LIBS)

chap10ex3_SOURCES = chap10ex3.cpp extcalibrefine.cpp readcalibrationdata.cpp

noinst_HEADERS = extcalibrefine.h readcalibrationdata.h

sandbin_DATA = calibration_data.txt
EXTRA_DIST = calibration_data.txt
