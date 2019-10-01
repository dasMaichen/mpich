prebuilt_cxx_library(
  name = 'mpich',
  soname = 'libmpi.so.12',
  static_lib = 'lib/libmpi.a',
  shared_lib = 'lib/libmpi.so.12.1.7',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include','**/*.h'),
  ]),
  visibility = ['PUBLIC']
)

