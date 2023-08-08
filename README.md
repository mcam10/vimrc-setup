# vimrc-setup
vimrc file 

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
syntax on
set nu
set relativenumber
set encoding=UTF-8
set smarttab
set smartindent
set tabstop=4 softtabstop=4
set shiftwidth=4
set expandtab
set re=0
set nowrap
set noswapfile
set incsearch
set scrolloff=8
set guicursor=

autocmd VimEnter * NERDTree
 
call vundle#begin()
 
" let Vundle manage Vundle, required
Plugin 'VundleVim/Vundle.vim'
 
" Vim Airline
Plugin 'vim-airline/vim-airline'
 
" Nerd Trees
Plugin 'scrooloose/nerdtree'
 
" Vim devicons
Plugin 'ryanoasis/vim-devicons'
call vundle#end() " required
