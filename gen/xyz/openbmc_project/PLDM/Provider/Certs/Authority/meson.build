# Generated file; do not modify.
subdir('CSR')
generated_others += custom_target(
    'xyz/openbmc_project/PLDM/Provider/Certs/Authority/CSR__markdown'.underscorify(),
    input: [ meson.source_root() / 'xyz/openbmc_project/PLDM/Provider/Certs/Authority/CSR.interface.yaml',  ],
    output: [ 'CSR.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.source_root(),
        'xyz/openbmc_project/PLDM/Provider/Certs/Authority/CSR',
    ],
    build_by_default: true,
)

