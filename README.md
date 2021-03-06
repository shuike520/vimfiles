# HungYuHei's vimrc

## Installtion

### 1. Backup your original vim files

```
mv ~/.vimrc ~/.vimrc_backup
mv ~/.vim ~/.vim_backup
```

### 2. Check out from github

```
git clone https://github.com/HungYuHei/vimfiles.git ~/.vim
```

### 3. Link ~/.vimrc

```
ln -s ~/.vim/vimrc ~/.vimrc
```

### 4. Install dependents

######Mac(homebrew) :

```
brew update
brew install ctags
brew install the_silver_searcher
```

######Ubuntu :

```
sudo apt-get install ctags
# Install the_silver_searcher, take a look at https://github.com/ggreer/the_silver_searcher
```

### 5. Fetch submodules

```
# run this command only if you are using server branch
cd ~/.vim/bundle && git rm --cache ctrlp delimitMate git_vim haml snipmate vim-slim ZoomWin

# you are required to run this commands
cd ~/.vim
git submodule init
git submodule update
```

That's it, enjoy!
please let me know if you have any issues.

## Keyboard shortcuts

**Please keep your mind that `<leader>` is set to `,`**

* `<F7>` Toggle NERDTreeFind
* `<F8>` Toggle NERDTree
* `<F9>` Toggle TagList
* `<F10>` Toggle paste mode
* `<leader><leader>` Trig EasyMotion (e.g. `<leader><leader>w` `<leader><leader>f` etc.)
* `<leader>s` Horizontally split window
* `<leader>v` Vertically split window
* `Ctrl-[hjkl]` Move between windows (left down up right)
* `Ctrl-p` Invoke ctrlP (reference: [ctrlP homepage](https://github.com/kien/ctrlp.vim))
* `<leader>a` `:Ag`
* `<F5>` copy the file's relative path to the clipboard
* `<leader>cp` copy the file's absoulte path to the clipboard
* `<leader>V` Reselect the text that was just pasted
* `<leader>w` Strip all trailing whitespace in the current file
* `<leader>lc` Toggle highlight cursor column
* `<leader>ll` Toggle highlight cursor line
* `<leader>ms` Display 80-column indication
* `<leader>mh` Hide 80-column indication
* `<leader>be` Toggle BufExplorer
* `<leader>c<space>` Toggle NERDCommenter
* `<leader>ig` Toggle indent guides

**Please reference to the plugin's homepage below to see more shortcuts**

## Plugins

* [The NERD tree](https://github.com/scrooloose/nerdtree) : A tree explorer plugin for navigating the filesystem
* [vim-surround](https://github.com/tpope/vim-surround) : Plugin for deleting, changing, and adding "surroundings"
* [BufExplorer](http://www.vim.org/scripts/script.php?script_id=42) : Quickly and easily switch between buffers
* [NERDCommenter](https://github.com/scrooloose/nerdcommenter) : A plugin that allows for easy commenting of code for many filetypes
* [snipMate](http://www.vim.org/scripts/script.php?script_id=2540) : TextMate-style snippets for Vim
* [TagList](http://www.vim.org/scripts/script.php?script_id=273) : Provide an overview of the structure of source code files
* [fugitive](https://github.com/tpope/vim-fugitive) : A Git wrapper so awesome, it should be illegal
* [the_silver_searcher](https://github.com/rking/ag.vim) : Vim plugin for the_silver_searcher, 'ag', a replacement for the Perl module / CLI script 'ack'
* [rails](http://www.vim.org/scripts/script.php?script_id=1567) : Ruby on Rails: easy file navigation, enhanced syntax highlighting, and more
* [delimitMate](http://www.vim.org/scripts/script.php?script_id=2754) : Provides auto-balancing and some expansions for parens, quotes, etc.
* [matchit](http://www.vim.org/scripts/script.php?script_id=39) : Extended % matching for HTML, LaTeX, and many other languages
* [EasyMotion](https://github.com/Lokaltog/vim-easymotion) : Vim motions on speed
* [ctrlP](https://github.com/kien/ctrlp.vim) : Fuzzy file, buffer, mru, tag, etc finder
* [indentLine](https://github.com/Yggdroot/indentLine) : A vim plugin to display the indention levels with thin vertical lines
* [vim-repeat](https://github.com/tpope/vim-repeat) : Enable repeating supported plugin maps with "."
* [Tabular](https://github.com/godlygeek/tabular) : Vim script for text filtering and alignment
* [zen-coding](https://github.com/mattn/zencoding-vim) : A web-developer’s toolkit that can greatly improve your HTML & CSS workflow
* [vim-javascript](https://github.com/pangloss/vim-javascript) : Provides syntax and indent plugins.
* [vim-coffee-script](https://github.com/kchmck/vim-coffee-script) : CoffeeScript support for vim.

## Screenshot

![vim-screenshot](http://ww2.sinaimg.cn/large/64af5c16jw1e7csl9xqgnj20k00f841k.jpg)
