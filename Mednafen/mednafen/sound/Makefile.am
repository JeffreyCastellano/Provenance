AUTOMAKE_OPTIONS = subdir-objects
DEFS = -DLOCALEDIR=\"$(datadir)/locale\" @DEFS@ 
DEFAULT_INCLUDES = -I$(top_builddir)/include -I$(top_srcdir)/include -I$(top_srcdir)/intl

noinst_LIBRARIES	=	libmdfnsound.a

libmdfnsound_a_SOURCES  =       Blip_Buffer.cpp Stereo_Buffer.cpp Fir_Resampler.cpp WAVRecord.cpp

libmdfnsound_a_SOURCES	+=	OwlResampler.cpp

libmdfnsound_a_SOURCES	+=	okiadpcm.cpp
