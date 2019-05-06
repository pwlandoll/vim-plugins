# vim-plugins
Submodule collection for vim 8 plugins

Followed pointers from [a helpful blog post](https://dvonrohr.com/2016/12/11/vim-package-manager/).

## Adding
To add a plugin, run `git submodule add <url> start/<plugin-name>`.

## Updating
All plugins are git submodules, update using `git submodule update --remote --merge`.

## Removing
To remove a plugin, run the following:
```
git submodule deinit start/<plugin-name>
git rm start/<plugin-name>
rm -rf .git/modules/start/<plugin-name>
```

## Others
Honorable mention goes to [peaksea](https://github.com/vim-scripts/peaksea) for colors.

## Modules used:
- [ale](https://github.com/w0rp/ale)
- [lightline](https://github.com/itchyny/lightline.vim)
- [NERDtree](https://github.com/scrooloose/nerdtree)
- [vim-go](https://github.com/fatih/vim-go)
- [vim-surround](https://github.com/tpope/vim-surround)
- [VimWiki](https://github.com/vimwiki/vimwiki)
