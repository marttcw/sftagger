project('sftagger'
  , 'c'
  , default_options : ['warning_level=3', 'c_std=c99', 'optimization=3', 'werror=false']
)

src_inc = include_directories('./src/')

src = [
    './src/main.c'
  , './src/tagger.c'
  , './src/impl/str.c'
  , './src/impl/file.c'
  , './src/hmap.c'
]

executable('sftagger'
           , sources : src
           , include_directories : [src_inc]
)


