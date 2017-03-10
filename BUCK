include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'sqlpp11',
  header_only = True,
  header_namespace = 'sqlpp11',
  exported_headers = subdir_glob([
    ('include/sqlpp11', '**/*.h'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
