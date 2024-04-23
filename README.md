## neovim setup

My personal neovim setup. Trying to keep it minimal.

Copy `lua.init` into `~/.config/nvim/init.lua` and make sure you have neovim
installed. Then just enter neovim.

### shortcuts

Note: leader is \

In normal mode:

- \sf = [S]earch [F]iles
- \sw = [S]earch current [W]ord
- \sg = [S]earch by [G]rep
- ,nt = toggle nvim tree
- ,ev = edit my init.lua config
- \c  = comment line/selection
- C   = change root dir in nvim tree
- K   = Opens a popup that displays documentation about the word under your cursor
- gd  = go to definition (Ctrl-t to go back)
- gr  = go to references (Ctrl-t to go back)
- Ctrl-q = move references to quicklist (THIS IS AWESOME!!)
- Ctrl-k = move to next reference from quicklist
- Ctrl-j = move to previous reference from quicklist
- \l = highlight current line (useful for pair programming)
- \, = remove all highlighted lines (with \ll)
- \u  = toggle undo tree
- \ee = insert golang if err snippet
- \xx = toggle trouble plugin -> a nicer quicklist with diagnostics
- ]t and [t = toggle between trouble list items (without manually going through
  the list - next and prev)

In insert mode:

- ,e     = Esc
- Ctrl-f = scroll [f]orward in autocomplete docs
- Ctrl-b = scroll [b]ack in autocomplete docs
- \ee    = insert golang if err snippet

### snippets

https://github.com/rafamadriz/friendly-snippets/blob/main/snippets/go.json

### attention!

Make sure you have `goimports` installed and the go bin path set into your
.bashrc / .zshrc:

```bash
go install golang.org/x/tools/cmd/goimports@latest
echo 'export PATH="$PATH:$HOME/go/bin"' >> ~/.zshrc
```
