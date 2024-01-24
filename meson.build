project('protobuf', 'c')
inc=include_directories('protobuf-c')
libproto = library('protobuf', 'protobuf-c/protobuf-c.c',
include_directories:inc,
)
dep_libproto = declare_dependency(
include_directories: inc,
link_with: [libproto],
)
