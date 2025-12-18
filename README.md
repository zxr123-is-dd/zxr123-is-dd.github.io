# zxr123-is-dd.github.io

## vim setting for competitive programming

```vim
set nu ts=4 sw=4 sts=4 et autoindent smartindent mouse=a bs=indent,eol,start
set background=dark
syntax on
autocmd BufNewfile *.cpp 0r ~/Documents/cp/template.cpp
nnoremap <F5> :w<CR>:!g++ -std=c++14 -O2 -Wall -Wextra % -o %:r && ./%:r < in<CR>
nnoremap <F6> : !./%:r < in<CR>
```

## codeforces rating
![](https://cfrating.baoshuo.dev/rating?username=zxr123)

## Learning OpenGL...

![The newbie OpenGL project :)](https://github.com/zxr123-is-dd/Project1forOpenGLLearning)
