
add_executable(rage)
target_sources(rage PRIVATE rage.c)
target_link_libraries(rage PRIVATE vendor)
