
# Configuração do Vim 


![version](https://img.shields.io/badge/version-1.0-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue.svg)

Este repositório contém um arquivo de configuração do **Vim** que utiliza o gerenciador de plugins `vim-plug`. A configuração inclui diversos plugins úteis e ajustes personalizados para melhorar a usabilidade do editor.

## Como Instalar
`git clone https://github.com/seu-usuario/vim-config.git` 
<br/>
<br/>
`curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`
<br/>
<br/>

`cp vim-config/.vimrc ~/.vimrc`
<br/>
<br/>
`:PlugInstall`
## Plugins Instalados


```vim
call plug#begin('~/.vim/plugged')
Plug 'terroo/vim-simple-emoji'
Plug 'matsuuu/pinkmare'
Plug 'dracula/vim', { 'as': 'dracula' }
Plug 'artanikin/vim-synthwave84'
Plug 'joshdick/onedark.vim'
Plug 'ycm-core/YouCompleteMe'
Plug 'jiangmiao/auto-pairs'
call plug#end()

