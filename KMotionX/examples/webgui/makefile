include $(BUILD_ROOT)/config.mak
#DEFS+=-DDEBUG
SOURCES=frozen.cpp mongoose.cpp handler.cpp webserver.cpp  
IDIR+=$(BUILD_ROOT)/KMotionX/include
IDIR+=$(BUILD_ROOT)/KMotionX/KMotionSupport/include
IDIR+=$(BUILD_ROOT)/KMotionDLL
IDIR+=$(BUILD_ROOT)/GCodeInterpreter
#DEFS+=-DNS_STACK_SIZE=500
LD_LIBS+=KMotionSupport
LD_LIBS+=KMotion
LD_LIBS+=GCodeInterpreter

EXECUTABLE=kmxWeb
SHARED=

include $(BUILD_ROOT)/include.mk




