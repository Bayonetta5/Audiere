# Audiere tweaked for 32/64 bit MSVC 2005 builds
Audiere tweaked to compile 32 bit and 64 bit binaries for MSVC 2005.  I couldn't find any existing ones, so here they are.  Includes all dependencies setup in one msvc 2005 solution.

To compile, open Audiere/vc8/audiere.sln

Versions used:
audiere: 1.9.4 (?) forked from Chad Austin's Audiere on github
flac: 1.3.1
libogg: 1.3.2
libvorbis: 1.3.5

Pre-compiled binaries available here: http://www.codedojo.com/?p=1977

NOTE: The 64 bit binaries are missing mod/xm playback because I was too lazy to find and compile Dumb.  Also missing speexfile support, whatever that is.

To-renable those, remove NO_DUMB and NO_SPEEX preprocessor definitions and add the libs.

Seth A Robinson
www.rtsoft.com
@rtsoft
