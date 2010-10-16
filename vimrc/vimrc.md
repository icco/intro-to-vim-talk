!SLIDE command
# .vimrc
 
!SLIDE
# Warning:
## I said it once I'll say it again,
# Vim is meant to be used the way you feel natural doing it.
## What works for me may not work for you.

!SLIDE
# My .vimrc
### <http://github.com/icco/dotFiles/blob/master/vimrc>
## Short URL: <http://is.gd/g4Pdj>

!SLIDE command
## Some basics
# set nocompatible
### Fuck vi.
# syntax on
### Highlight your syntax
# set number
### Number your lines fool
# set showmode
### Show what mode you're in

!SLIDE command
## Wrapping
# set expandtab 
### expand tabs with spaces
# set tabstop=3  
### <Tab> move three characters
# set shiftwidth=3
### >> and << shift 3 spaces
# "set textwidth=79
### hard wrap at 79 characters
# set softtabstop=3
### see spaces as tabs

!SLIDE
# modelines
## `set modeline`
## `vim: set filetype=sh:`
### check for a modeline

!SLIDE bullets
# keybindings

 * vmap is for visual mode
 * imap is for insert mode 
 * nmap is for command mode
 * nore - don't check for recursive mappings.

!SLIDE small
# keybinding examples

## Because we like our line numbers sometimes...
### `:nnoremap <C-N><C-N> :set invnumber<CR>`

## But we don't always wanna wrap
### `:nnoremap <C-w><C-w> :set invwrap<CR>`
 
## And all the cool kids need to paste
### `:nnoremap <C-p><C-p> :set invpaste<CR>`
 
## Use the space key to open and close code folds
### `:vnoremap <space> zf<CR>`
### `:nnoremap <space> zd<CR>`

!SLIDE command
## tabs and workspaces

# :vs, :sp, ctrl + w

# :tabnew, :tabclose, :tabn, :tabp

### But seriously, let me just show you...
