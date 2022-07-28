srcs = files('api.c', 'dumper.c', 'emitter.c', 'loader.c', 'parser.c', 'reader.c', 'scanner.c', 'writer.c')

libyaml = library('yaml', srcs,
    c_args: '-DHAVE_CONFIG_H',
    include_directories: inc,
    install: true,
    version: meson.project_version(),
    soversion: 0)
