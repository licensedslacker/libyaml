dep = declare_dependency(include_directories: [inc], link_with: [libyaml])

test('test-reader', executable('test-reader', 'test-reader.c', dependencies: [dep]))
test('test-version', executable('test-version', 'test-version.c', dependencies: [dep]))

executable('run-dumper', 'run-dumper.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-emitter-test-suite', 'run-emitter-test-suite.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-emitter', 'run-emitter.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-loader', 'run-loader.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-parser-test-suite', 'run-parser-test-suite.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-parser', 'run-parser.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))
executable('run-scanner', 'run-scanner.c', dependencies: [dep], build_by_default: get_option('build_test_apps'))

executable('example-deconstructor-alt', 'example-deconstructor-alt.c', dependencies: [dep], build_by_default: get_option('build_examples'))
executable('example-deconstructor', 'example-deconstructor.c', dependencies: [dep], build_by_default: get_option('build_examples'))
executable('example-reformatter-alt', 'example-reformatter-alt.c', dependencies: [dep], build_by_default: get_option('build_examples'))
executable('example-reformatter', 'example-reformatter.c', dependencies: [dep], build_by_default: get_option('build_examples'))
