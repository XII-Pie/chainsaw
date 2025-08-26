aux_source_directory(. COMMON_SRC)

add_subdirectory(stringtool)

add_library(common ${COMMON_SRC})

target_include_directories(common PUBLIC include)
