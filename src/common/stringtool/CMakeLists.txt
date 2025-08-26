aux_source_directory(. src)

add_library(stringtool ${src})
target_include_directories(stringtool PUBLIC include)
