Replaced in the QZXIng cmake file Qt5 -> Qt6
and set
if(QZXING_MULTIMEDIA)

    LIST(APPEND SOURCES QZXingFilterVideoSink.cpp QZXingFilterVideoSink.h)
    add_definitions(-DQZXING_MULTIMEDIA)

    SET(QZXING_USE_QML ON)

endif(QZXING_MULTIMEDIA)

instead of QZXingFilter.[cpp,h]
