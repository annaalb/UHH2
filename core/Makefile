LIBRARY := SUHH2core
DICT := include/AnalysisModuleRunner.h include/NtupleObjects.h include/SUHH2core_LinkDef.h

FJINC=/nfs/dust/cms/user/albrecha/uhh2_102X/fastjet-install/include
FJLIB=/nfs/dust/cms/user/albrecha/uhh2_102X/fastjet-install/lib

USERLDFLAGS := -Wl,-rpath,${FJLIB} -lm -L${FJLIB} -lfastjettools -lfastjet -lHOTVR -lNsubjettiness -lRecursiveTools
USERCXXFLAGS := -I${FJINC}

TEST := 1
TESTPAR := 1
include ../Makefile.common
