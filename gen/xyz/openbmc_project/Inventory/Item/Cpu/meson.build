# Generated file; do not modify.
generated_sources += custom_target(
    'xyz/openbmc_project/Inventory/Item/Cpu__cpp'.underscorify(),
    input: [ meson.source_root() / 'xyz/openbmc_project/Inventory/Item/Cpu.interface.yaml',  ],
    output: [ 'server.cpp', 'server.hpp', 'client.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.source_root(),
        'xyz/openbmc_project/Inventory/Item/Cpu',
    ],
)

subdir('OperatingConfig')
generated_others += custom_target(
    'xyz/openbmc_project/Inventory/Item/Cpu/OperatingConfig__markdown'.underscorify(),
    input: [ meson.source_root() / 'xyz/openbmc_project/Inventory/Item/Cpu/OperatingConfig.interface.yaml',  ],
    output: [ 'OperatingConfig.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.source_root(),
        'xyz/openbmc_project/Inventory/Item/Cpu/OperatingConfig',
    ],
    build_by_default: true,
)

