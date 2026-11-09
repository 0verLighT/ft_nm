project(
  'ft_nm',
  'c',
  version: '0.1',
  license: 'MIT',
  meson_version: '>= 0.64.0',
  default_options : [
      'warning_level=2',
  ]
)

include = include_directories('include')

sources = files(
  'src/main.c'
)

executable(
  meson.project_name(),
  sources,
  include_directories: include
)
