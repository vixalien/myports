files = [
  'canopy',
  'system-branch',
  'tty-earlier@',
  'tty-rc@',
]

conf = configuration_data()
conf.set('VERSION', meson.project_version())

foreach file : files
  configure_file(
    input: file,
    output: file,
    configuration: conf
  )
endforeach
