# vimconfig
自己用的vim插件
# 使用方法：
1. 在/root目录下创建.vim目录；
2. 将此文件中的所有内容拷贝至.vim目录；
3. 修改/etc/vimrc，添加下面三行
```
execute pathogen#infect()
"magic key
map<S-n> :NERDTreeToggle<CR>
map<S-t> :TlistToggle<CR>

```
