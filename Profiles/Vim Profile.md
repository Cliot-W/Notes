# Vim Profile
```
syntax on                     " 设置语法高亮                                                                                                                                                                              
set nu                        " 设置行数显示
set tabstop=4                 " 设置tab缩进长度为4空格
set autoindent                " 设置自动缩进，适用所有类型文件
set cindent                   " 针对C语言的自动缩进功能，在C语言的编程环境中，比autoindent更加精准
set list lcs=tab:\|\          " 设置tab提示符号为 "|"，注意最后一个反斜杠后面要留有空格
set cc=0                      " 设置高亮的列，这里设置为0，代表关闭
set cursorline                " 突出显示当前行

```