load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'irrxml',
  srcs = glob(['src/*.cpp']),
  exported_headers = subdir_glob([('src', '*.h')]),
  visibility = ['PUBLIC']
)
