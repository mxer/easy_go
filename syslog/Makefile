# subdir and objects in current dir
SUBDIRS	= 
OBJECTS	= syslog.o


all:subdirs ${OBJECTS}
	ar r libsyslog.a $(OBJECTS)
#	ar r $@ $+

clean:cleansubdirs
	rm -f ${OBJECTS}
	
include ${MK_CF}
