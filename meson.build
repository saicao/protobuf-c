project('protobuf', 'c')
lib = library('protobuf', 'protobuf-c/protobuf-c.c')
protobuf = declare_dependency(
    link_with: lib,
    include_directories: [include_directories('protobuf-c')])
