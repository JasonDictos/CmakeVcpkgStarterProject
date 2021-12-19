find_package(fmt CONFIG REQUIRED)

add_executable(Example main.cpp)

target_link_libraries(Example PRIVATE fmt::fmt-header-only)