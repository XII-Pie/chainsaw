include_directories(include)

add_library(error_message error_message.cpp)
target_link_directories(include)

set_target_properties(error_message PROPERTIES
    PUBLIC_HEADER "include/error_message.h"
)
