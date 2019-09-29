prebuilt_cxx_library(
  name = 'mpich',
  soname = 'libmpi.so',
  static_lib = 'lib/libmpi.a',
  shared_lib = 'lib/libmpi.so',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include','**/*.h'),
  ]),
  visibility = ['PUBLIC']
)

