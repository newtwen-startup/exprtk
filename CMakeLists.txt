cmake_minimum_required (VERSION 3.8)


project (exprtk)


# Add source to this project's executable.
add_library (exprtk INTERFACE exprtk.hpp)
target_compile_options(exprtk INTERFACE -W3)