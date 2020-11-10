project('stb', 'c', default_options: ['c_std=gnu11'])

incs = [ include_directories('./')]
srcs = ['impl.c']
stb = static_library('stb',
                      srcs,
                      include_directories : incs)

stb_dep = declare_dependency(include_directories : incs,
                             link_with : stb)
