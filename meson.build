project('protobuf', 'c')
inc=include_directories('protobuf-c')
libproto = library('protobuf', 'protobuf-c/protobuf-c.c',
include_directories:inc,
)
libproto_dep = declare_dependency(
include_directories: inc,
link_with: [libproto],
)
pkg = import('pkgconfig')
pkg.generate(libproto,
  description: 'protobuf',
)