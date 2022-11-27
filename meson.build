project('stdc-shim', 'c')

sources = ['src/string.c', 'src/stdlib.c']

inc = include_directories('include')
lib = static_library('stdc-shim',sources: sources, include_directories: inc)
dep = declare_dependency(link_with: lib, include_directories: inc)

