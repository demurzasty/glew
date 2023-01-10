cmake_minimum_required (VERSION 3.16)

add_library (glew STATIC "src/glew.c")
target_include_directories (glew PUBLIC "include")
target_compile_definitions (glew PUBLIC GLEW_STATIC)
