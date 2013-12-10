ofxAfterEffects
===============

This is not working yet… its just a concept addon atm.


============================================================ IMPORTANT

All the AE header files are unchanged but one,
had to make a small addition to,
libs/Headers/A.h
for it to compile correctly.

//------------------------------------------ JULAPY ADDITION
#include "AEConfig.h"
#ifdef AE_OS_MAC
    #import <Cocoa/Cocoa.h>
#endif
//------------------------------------------

Later down the track, it would be good to have it compiling without this addition.

============================================================