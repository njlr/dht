cxx_library(
  name = 'dht',
  header_namespace = '',
  exported_headers = [
    'dht.h',
  ],
  srcs = [
    'dht.c',
  ],
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'example',
  srcs = [
    'dht-example.c',
  ],
  deps = [
    ':dht',
  ],
)
