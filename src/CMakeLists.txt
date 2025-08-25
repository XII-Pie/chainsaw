add_subdirectory(argv)
add_subdirectory(common)
add_subdirectory(error_message)
add_subdirectory(html)

add_library(chainsaw1.0.2
    argv
    common
    error_message
    html
)

target_include_directories(chainsaw1.0.2 
PUBLIC
.
)
