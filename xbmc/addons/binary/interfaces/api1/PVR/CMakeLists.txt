set(SOURCES AddonCallbacksPVR.cpp)

set(HEADERS AddonCallbacksPVR.h)

core_add_library(api1AddonCallbacks_PVR)

if(ENABLE_INTERNAL_FFMPEG)
  add_dependencies(api1AddonCallbacks_PVR ffmpeg)
endif()
