include ../../ThirdParty/PSCommon/BuildSystem/CommonDefs.mak

BIN_DIR = ../../Bin

INC_DIRS = \
	../../Include \
	../Common

SRC_FILES = *.cpp

USED_LIBS += OpenNI2

EXE_NAME = DataCollector

CFLAGS += -Wall

CFLAGS+=`pkg-config --cflags opencv`
LDFLAGS+=`pkg-config --libs opencv`

include ../../ThirdParty/PSCommon/BuildSystem/CommonCppMakefile
