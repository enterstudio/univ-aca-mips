#############################################################################
# Makefile for building: fonts
# Generated by qmake (1.07a) (Qt 3.3.8) on: Wed Oct  9 10:41:17 2013
# Project:  fonts.pro
# Template: subdirs
# Command: $(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile fonts.pro
#############################################################################

MAKEFILE =	Makefile
QMAKE    =	qmake
DEL_FILE =    rm -f
CHK_DIR_EXISTS= test -d
MKDIR    = mkdir -p
INSTALL_FILE= 
INSTALL_DIR = 
SUBTARGETS =	 \
		sub-simple-qfont-demo

first: all

all: Makefile $(SUBTARGETS)

simple-qfont-demo/$(MAKEFILE): 
	@$(CHK_DIR_EXISTS) "simple-qfont-demo" || $(MKDIR) "simple-qfont-demo"
	cd simple-qfont-demo && $(QMAKE) simple-qfont-demo.pro -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o $(MAKEFILE)
sub-simple-qfont-demo: simple-qfont-demo/$(MAKEFILE) FORCE
	cd simple-qfont-demo && $(MAKE) -f $(MAKEFILE)


Makefile: fonts.pro ../../.qmake.cache /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++/qmake.conf 
	$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile fonts.pro
qmake: qmake_all
	@$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile fonts.pro

all: $(SUBTARGETS)
qmake_all: simple-qfont-demo/$(MAKEFILE)
	 ( [ -d simple-qfont-demo ] && cd simple-qfont-demo ; grep "^qmake_all:" $(MAKEFILE) && $(MAKE) -f $(MAKEFILE) qmake_all; ) || true
clean uicables mocables uiclean mocclean lexclean yaccclean : qmake_all FORCE
	 ( [ -d simple-qfont-demo ] && cd simple-qfont-demo ; $(MAKE) -f $(MAKEFILE) $@; ) || true
uninstall_subdirs: qmake_all FORCE
	 ( [ -d simple-qfont-demo ] && cd simple-qfont-demo ; $(MAKE) -f $(MAKEFILE) uninstall; ) || true
install_subdirs: qmake_all FORCE
	 ( [ -d simple-qfont-demo ] && cd simple-qfont-demo ; $(MAKE) -f $(MAKEFILE) install; ) || true
distclean: qmake_all FORCE
	 ( [ -d simple-qfont-demo ] && cd simple-qfont-demo ; $(MAKE) -f $(MAKEFILE) $@; $(DEL_FILE) $(MAKEFILE); ) || true

install:  install_subdirs

uninstall:  uninstall_subdirs

FORCE:

