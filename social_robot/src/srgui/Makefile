#############################################################################
# Makefile for building: srgui
# Generated by qmake (2.01a) (Qt 4.6.2) on: Sat Nov 10 23:19:43 2012
# Project:  srgui.pro
# Template: app
# Command: /usr/bin/qmake-qt4 -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile srgui.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -g -I/usr/include/opencv-2.3.1/opencv -I/usr/include/opencv-2.3.1 -Wall -W -D_REENTRANT $(DEFINES)
CXXFLAGS      = -pipe -g -I/usr/include/opencv-2.3.1/opencv -I/usr/include/opencv-2.3.1 -Wall -W -D_REENTRANT $(DEFINES)
INCPATH       = -I/usr/share/qt4/mkspecs/linux-g++ -I. -I/usr/include/qt4/QtCore -I/usr/include/qt4/QtGui -I/usr/include/qt4 -I. -I.
LINK          = g++
LFLAGS        = 
LIBS          = $(SUBLIBS)  -L/usr/lib -lopencv_contrib -lopencv_legacy -lopencv_objdetect -lopencv_calib3d -lopencv_features2d -lopencv_video -lopencv_highgui -lopencv_ml -lopencv_imgproc -lopencv_flann -lopencv_core -lQtGui -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /usr/bin/qmake-qt4
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = ./

####### Files

SOURCES       = main.cpp \
		gui.cpp \
		imageframe.cpp \
		window_QT.cpp moc_gui.cpp \
		moc_imageframe.cpp \
		moc_window_QT.cpp \
		qrc_window_QT.cpp
OBJECTS       = main.o \
		gui.o \
		imageframe.o \
		window_QT.o \
		moc_gui.o \
		moc_imageframe.o \
		moc_window_QT.o \
		qrc_window_QT.o
DIST          = /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/link_pkgconfig.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		srgui.pro
QMAKE_TARGET  = srgui
DESTDIR       = 
TARGET        = srgui

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile $(TARGET)

$(TARGET): ui_gui.h $(OBJECTS)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJCOMP) $(LIBS)

Makefile: srgui.pro  /usr/share/qt4/mkspecs/linux-g++/qmake.conf /usr/share/qt4/mkspecs/common/g++.conf \
		/usr/share/qt4/mkspecs/common/unix.conf \
		/usr/share/qt4/mkspecs/common/linux.conf \
		/usr/share/qt4/mkspecs/qconfig.pri \
		/usr/share/qt4/mkspecs/features/qt_functions.prf \
		/usr/share/qt4/mkspecs/features/qt_config.prf \
		/usr/share/qt4/mkspecs/features/exclusive_builds.prf \
		/usr/share/qt4/mkspecs/features/default_pre.prf \
		/usr/share/qt4/mkspecs/features/debug.prf \
		/usr/share/qt4/mkspecs/features/default_post.prf \
		/usr/share/qt4/mkspecs/features/link_pkgconfig.prf \
		/usr/share/qt4/mkspecs/features/warn_on.prf \
		/usr/share/qt4/mkspecs/features/qt.prf \
		/usr/share/qt4/mkspecs/features/unix/thread.prf \
		/usr/share/qt4/mkspecs/features/moc.prf \
		/usr/share/qt4/mkspecs/features/resources.prf \
		/usr/share/qt4/mkspecs/features/uic.prf \
		/usr/share/qt4/mkspecs/features/yacc.prf \
		/usr/share/qt4/mkspecs/features/lex.prf \
		/usr/share/qt4/mkspecs/features/include_source_dir.prf \
		/usr/lib/libQtGui.prl \
		/usr/lib/libQtCore.prl
	$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile srgui.pro
/usr/share/qt4/mkspecs/common/g++.conf:
/usr/share/qt4/mkspecs/common/unix.conf:
/usr/share/qt4/mkspecs/common/linux.conf:
/usr/share/qt4/mkspecs/qconfig.pri:
/usr/share/qt4/mkspecs/features/qt_functions.prf:
/usr/share/qt4/mkspecs/features/qt_config.prf:
/usr/share/qt4/mkspecs/features/exclusive_builds.prf:
/usr/share/qt4/mkspecs/features/default_pre.prf:
/usr/share/qt4/mkspecs/features/debug.prf:
/usr/share/qt4/mkspecs/features/default_post.prf:
/usr/share/qt4/mkspecs/features/link_pkgconfig.prf:
/usr/share/qt4/mkspecs/features/warn_on.prf:
/usr/share/qt4/mkspecs/features/qt.prf:
/usr/share/qt4/mkspecs/features/unix/thread.prf:
/usr/share/qt4/mkspecs/features/moc.prf:
/usr/share/qt4/mkspecs/features/resources.prf:
/usr/share/qt4/mkspecs/features/uic.prf:
/usr/share/qt4/mkspecs/features/yacc.prf:
/usr/share/qt4/mkspecs/features/lex.prf:
/usr/share/qt4/mkspecs/features/include_source_dir.prf:
/usr/lib/libQtGui.prl:
/usr/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec /usr/share/qt4/mkspecs/linux-g++ -unix CONFIG+=debug -o Makefile srgui.pro

dist: 
	@$(CHK_DIR_EXISTS) .tmp/srgui1.0.0 || $(MKDIR) .tmp/srgui1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .tmp/srgui1.0.0/ && $(COPY_FILE) --parents gui.h imageframe.h window_QT.h .tmp/srgui1.0.0/ && $(COPY_FILE) --parents window_QT.qrc .tmp/srgui1.0.0/ && $(COPY_FILE) --parents main.cpp gui.cpp imageframe.cpp window_QT.cpp .tmp/srgui1.0.0/ && $(COPY_FILE) --parents gui.ui .tmp/srgui1.0.0/ && (cd `dirname .tmp/srgui1.0.0` && $(TAR) srgui1.0.0.tar srgui1.0.0 && $(COMPRESS) srgui1.0.0.tar) && $(MOVE) `dirname .tmp/srgui1.0.0`/srgui1.0.0.tar.gz . && $(DEL_FILE) -r .tmp/srgui1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all: moc_gui.cpp moc_imageframe.cpp moc_window_QT.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) moc_gui.cpp moc_imageframe.cpp moc_window_QT.cpp
moc_gui.cpp: window_QT.h \
		gui.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) gui.h -o moc_gui.cpp

moc_imageframe.cpp: imageframe.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) imageframe.h -o moc_imageframe.cpp

moc_window_QT.cpp: window_QT.h
	/usr/bin/moc-qt4 $(DEFINES) $(INCPATH) window_QT.h -o moc_window_QT.cpp

compiler_rcc_make_all: qrc_window_QT.cpp
compiler_rcc_clean:
	-$(DEL_FILE) qrc_window_QT.cpp
qrc_window_QT.cpp: window_QT.qrc \
		files_Qt/Milky/48/28.png \
		logomulti.png \
		files_Qt/Milky/48/24.png \
		files_Qt/Milky/48/61.png \
		logo.png \
		files_Qt/Milky/48/38.png \
		files_Qt/Milky/48/107.png \
		files_Qt/Milky/48/27.png \
		files_Qt/Milky/48/106.png \
		files_Qt/Milky/48/19.png \
		files_Qt/stylesheet_trackbar.qss \
		files_Qt/Milky/48/7.png \
		files_Qt/Milky/48/23.png
	/usr/bin/rcc -name window_QT window_QT.qrc -o qrc_window_QT.cpp

compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all: ui_gui.h
compiler_uic_clean:
	-$(DEL_FILE) ui_gui.h
ui_gui.h: gui.ui \
		imageframe.h
	/usr/bin/uic-qt4 gui.ui -o ui_gui.h

compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean compiler_rcc_clean compiler_uic_clean 

####### Compile

main.o: main.cpp gui.h \
		window_QT.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o main.o main.cpp

gui.o: gui.cpp gui.h \
		window_QT.h \
		ui_gui.h \
		imageframe.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o gui.o gui.cpp

imageframe.o: imageframe.cpp imageframe.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o imageframe.o imageframe.cpp

window_QT.o: window_QT.cpp window_QT.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o window_QT.o window_QT.cpp

moc_gui.o: moc_gui.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_gui.o moc_gui.cpp

moc_imageframe.o: moc_imageframe.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_imageframe.o moc_imageframe.cpp

moc_window_QT.o: moc_window_QT.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o moc_window_QT.o moc_window_QT.cpp

qrc_window_QT.o: qrc_window_QT.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o qrc_window_QT.o qrc_window_QT.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

