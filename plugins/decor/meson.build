decoration = shared_module('decoration',
    ['decoration.cpp', 'deco-subsurface.cpp', 'deco-button.cpp',
      'deco-layout.cpp', 'deco-theme.cpp'],
    include_directories: [wayfire_api_inc, wayfire_conf_inc],
    dependencies: [wlroots, pixman, wf_protos, wfconfig, cairo],
    install: true,
    install_dir: join_paths(get_option('libdir'), 'wayfire'))

install_subdir('resources', install_dir: 'share/wayfire/decoration')
