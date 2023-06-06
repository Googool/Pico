FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/core/source/*.*)
idf_component_register(SRCS ${app_sources})
