project('Yoga',
        'c','cpp',
        default_options: [
        'warning_level=2',
        'cpp_std=c++20',
    ]
)

cmake = import('cmake')

# Configure the CMake project
yoga_subproject = cmake.subproject('yoga')

# Fetch the dependency object
yoga_cmake = yoga_subproject.dependency('yogacore')

# yoga = library(
#     'Yoga',
#     dependencies : yoga_cmake,
#     install : true
# )
