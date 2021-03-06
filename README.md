# [Gumernus's](https://github.com/gumernus) personal vim configuration
## Features
- Multitasking
- Better support for Javascript, Typescript and C++ (contact me for including better support for your fav language)
- Good keymapping
- Lightweight and fast

![image](https://user-images.githubusercontent.com/70224036/168889002-f8145220-b0e5-41a1-b206-e77a116d27e2.png)

## Installation
#### Download .vimrc (in terminal)
```
git clone https://github.com/gumernus/vimrc
```
```
cd vimrc
```
```
mv .vimrc ~/.vimrc
```

#### Install vim-plug (in terminal)
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

```
#### Plug all plugins (in vim)
Go thru all errors and then type `:`
```
source %
```
```
PlugInstall
```
## Mapping 

#### In Files
- CTRL + ww `jump between windows`
- CTRL + a `comment/uncomment`
- CTRL + b `toggle file tree`
- CTRL + d `open terminal`
- 
#### In File Tree
- SHIFT + r `refresh file tree`
- SHIFT + i `toggle hidden files`
