## This is my nvim configuration
# Plugins
- Theme
    - nightfly
- Coc
- NerdTree
- LuaLine
- Icons
    - Nvim web devicons
    - Vim devicons
- Buftables
- rnvimr
- Dashboard nvim
- Telescope
    - Telescope
    - Plenary nvim

In my case for the plugins I use [vim-plug](https://github.com/junegunn/vim-plug) for install this plugin manager use this command in linux.

```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

For other SO use the instalation it is redacted in the doc of [vim-plug](https://github.com/junegunn/vim-plug).

Also I use COC for the auto completation and you must install nodejs in some oficial repositoris has this pack but other linux repositoris not if yours dont have it use the command:

```
curl -sL install-node.vercel.app/lts | bash
```

If you have more problems read it in the oficial page of [COC.nvim](https://github.com/neoclide/coc.nvim)
