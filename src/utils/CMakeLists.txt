# Required to generate MOC
target_sources(
  flameshot
  PRIVATE dbusutils.h
          filenamehandler.h
          screengrabber.h
          systemnotification.h
          valuehandler.h
          request.h
          strfparse.h
)

target_sources(
  flameshot
  PRIVATE filenamehandler.cpp
          screengrabber.cpp
          confighandler.cpp
          systemnotification.cpp
          valuehandler.cpp
          screenshotsaver.cpp
          dbusutils.cpp
          globalvalues.cpp
          desktopfileparse.cpp
          desktopinfo.cpp
          pathinfo.cpp
          colorutils.cpp
          history.cpp
          strfparse.cpp
        request.cpp
)
