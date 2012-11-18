# vim-locate

A vim plugin that integrates the unix locate database, allowing fast
partial case-insensitive file name searching. Matching files are loaded
in a locate window list.

## Installation

Copy the `locate.vim` file to `~/.vim/plugins` and add the following
to your `~/.vimrc` configuration to invoke with F4:

    nnoremap <silent> <F4> :Locate<CR>

## Usage

Use `:Locate`, press F4, or select `Tools --> Search --> File Names`. 
The word currently under the cursor will be pre-selected. A readline
history is maintained of previous search phrases.

## License

Copyright © 2012 Richard Hull

Distributed under the Eclipse Public License.
