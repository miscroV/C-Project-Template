project(Template-c)
cmake_minimum_required(VERSION 3.13)
set(CMAKE_C_STANDARD 99)


file(GLOB SOURCE_FILES "src/*.c" "inc/*.h")
add_executable(Template ${SOURCE_FILES})

target_include_directories(Template PUBLIC inc)

