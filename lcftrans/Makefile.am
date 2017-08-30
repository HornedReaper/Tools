bin_PROGRAMS = lcftrans
lcftrans_SOURCES = \
	src/main.cpp \
	src/translation.cpp \
	src/translation.h \
	src/dirent_win.h
lcftrans_CXXFLAGS = \
	-std=c++11 \
	$(LCF_CFLAGS)
lcftrans_LDADD = \
	$(LCF_LIBS)

EXTRA_DIST = README.md
