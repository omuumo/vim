# Vim
Vim Configuration

使用 [vim-plug](https://github.com/junegunn/vim-plug) 管理插件，所以需要先安装 vim-plug

## 配置之前
```
# 安装 vim-plug
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

# 获取本项目配置
git clone https://github.com/clopend/vimrc.git
```
## 配置
```
cp ./vimrc/.vimrc ~/

vim ~/.vimrc

:PlugInstall
```
