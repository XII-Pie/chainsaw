include_directories(include)

add_library(error_message print_err.cpp)
target_link_directories(error_message PUBLIC include)

# set_target_properties(error_message PROPERTIES
#     PUBLIC_HEADER "include/error_message.h"
# )
