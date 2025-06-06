project('liba',
        'c',
        default_options: [
          'buildtype=debugoptimized',
        ])

liba = static_library('a',
                      sources: ['liba.c'])

liba_dep = declare_dependency(link_with : liba)
