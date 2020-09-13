installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins CutListEditor PicturePlayer MediaScanner SocketMMI DVDBurn MediaPlayer

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if ENABLE_SPARK7162
SUBDIRS += spark7162VFD
endif
 
if ENABLE_SPARK
SUBDIRS += sparkVFD
endif

install_PYTHON = __init__.py
