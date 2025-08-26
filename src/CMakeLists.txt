include_directories(.)

add_subdirectory(argv)
add_subdirectory(common)
add_subdirectory(error_message)
add_subdirectory(html)

add_library(chainsaw STATIC
    argv
    common
    error_message
    html
)

# 设置版本号（可选）
set_target_properties(chainsaw PROPERTIES
    VERSION "1.0.2"
    SOVERSION "1"
)