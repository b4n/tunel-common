
lib_LTLIBRARIES = libtlcommon.la

#libtlcommon_la_CPPFLAGS = @TL_PHY_DEBUG_CPPFLAGS_EXPORT@
libtlcommon_la_CFLAGS   = @TL_COMMON_CFLAGS@
libtlcommon_la_CXXFLAGS = @TL_COMMON_CXXFLAGS@
libtlcommon_la_LDFLAGS  = -version-info @TL_COMMON_LTVERSION@
libtlcommon_la_LIBADD   = @TL_COMMON_LIBS@
libtlcommon_la_SOURCES  = socket.c \
                          ptimer.c \
                          netclient.c \
                          netprotocol.c \
                          netserver.c \
                          terrainbrush.c \
                          position.c \
                          physics.cpp \
                          character.c \
                          treegenerator.c


tl_include_common_HEADERS = socket.h \
                            ptimer.h \
                            netclient.h \
                            netprotocol.h \
                            netserver.h \
                            terrainbrush.h \
                            position.h \
                            physics.h \
                            character.h \
                            treegenerator.h
