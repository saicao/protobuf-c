project('protobuf', 'c')
protobuf_lib = library('protobuf', 'protobuf-c/protobuf-c.c')
protobuf_c = declare_dependency(
    link_with: protobuf_lib,
    include_directories: [include_directories('protobuf-c')])
