# IdeaVIM-config
Vim configuration file for the IdeaVim Plugin from IntelliJ or other Jetbrains IDEs.

## Vim Configuration
Some configurations doesn't work if you put into `/.ideavimrc` file. Instead, you can edit the `~.vimrc` directly with these options.

```
" Set space as Leader key
nnoremap <SPACE> <Nop>
let mapleader=" "

" Fast saving
nmap <leader>s :w!<cr>

" Exiting modes fast
vmap jk <Esc>
vmap kj <Esc>
imap jk <Esc>
imap kj <Esc>
```
