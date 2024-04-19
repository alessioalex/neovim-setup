## neovim setup

My personal neovim setup. Trying to keep it minimal.

Copy `lua.init` into `~/.config/nvim/init.lua` and make sure you have neovim
installed. Then just enter neovim.

### shortcuts

Note: <leader> is \

In normal mode:

- \sf = [S]earch [F]iles
- \sw = [S]earch current [W]ord
- \sg = [S]earch by [G]rep
- ,nt = toggle nvim tree
- ,ev = edit my init.lua config
- \c  = comment line/selection
- C   = change root dir in nvim tree
- K   = Opens a popup that displays documentation about the word under your cursor
- gd  = go to definition (<C-t> to go back)
- gr  = go to references (<C-t> to go back)
- \q  = references to quicklist
- <C-k> = move to next reference from quicklist
- <C-j> = move to previous reference from quicklist

In insert mode:

- ,e    = <Esc>
- <C-f> = scroll forward in autocomplete docs
- <C-b> = scroll back in autocomplete docs

### snippets

https://github.com/rafamadriz/friendly-snippets/blob/main/snippets/go.json
