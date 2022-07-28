project('libyaml', 'c',
    version: '0.2.5',
    default_options: 'warning_level=3')

conf = configuration_data()
conf.set('PACKAGE', 'yaml')
conf.set('PACKAGE_NAME', 'yaml')
conf.set_quoted('PACKAGE_VERSION', meson.project_version())
conf.set_quoted('VERSION', meson.project_version())
conf.set_quoted('YAML_VERSION_STRING', meson.project_version())
conf.set('YAML_VERSION_MAJOR', 0)
conf.set('YAML_VERSION_MINOR', 2)
conf.set('YAML_VERSION_PATCH', 5)

subdir('include')
subdir('src')
subdir('tests')
