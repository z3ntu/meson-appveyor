project('meson-appveyor', 'c',
  version : '1.0',
  default_options : ['warning_level=3'])

lib = library('lib', 'helloworldlib.c')

exe = executable('meson_appveyor',
                 'helloworld.c',
                 link_with: lib,
                 install : true)

test('basic', exe)
