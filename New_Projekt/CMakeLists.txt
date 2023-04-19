# define the minimum cmake version
cmake_minimum_required(VERSION 3.16)

# define the project name
project(Programmentwurf VERSION 1.0 LANGUAGES CXX)

# define the c standard version
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# add some compile options
add_compile_options(-Wall -Wextra -pedantic -O0)

# add a library for your functions
#add_library(Programm_lib STATIC
#    src/developer.c
#    src/developer_group.c)
# add the includes to the library
#target_include_directories(Programm_lib PUBLIC include)

# add an executabel and assign files to it
add_executable(Programmentwurf main.cpp)
# add the include directories
#target_include_directories(Programmentwurf PRIVATE include)
# link your library
#target_link_libraries(Programmentwurf PRIVATE Programm_lib)