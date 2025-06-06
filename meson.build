project('myapp', 'c')

liba_dep = subproject('liba').get_variable('liba_dep')

exe = executable('myapp',
                 sources: ['main.c'],
                 dependencies: [liba_dep])
