libntr_link_args = []

libntr_exe = executable(
    'libntrwifi',
    sources: files('main.c'),
    dependencies: [ nitrosdk_dep, nitrowifi_dep ],
    link_args: [ libntr_link_args ],
    native: build_target != 'arm',
)
