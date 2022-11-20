project(
  'icu',
  # Uncomment to have a working linker
  # 'c',
  'nasm',
  version: '72.1'
)

U_ICU_VERSION = meson.project_version()

sources = files('icudt72.asm')

icudata = library(
    'icudt',
    sources,
    version: U_ICU_VERSION,
    vs_module_defs: 'module.def',
    install: true,
)
