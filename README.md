&copy; Carlos Contreras
carloscontrerasc@gmail.com

Configuration configuration folders
==================================

Installation
------------

Create `dotfiles` folder, clone, and create symbolic links (this will overwrite existing configuration files)

    mkdir ~/dotfiles
	cd ~/dotfiles
	git clone https://gitlab.com/ccontreras4/dotfiles.git
	ln -sfT ~/dotfiles/dottmux.conf ~/.tmux.conf
	ln -sfT ~/dotfiles/dotbashrc ~/.bashrc
	ln -sfT ~/dotfiles/dotbashpromt ~/.bashprompt
	ln -sfT ~/dotfiles/dotvimrc ~/.vimrc
    


bash
----

### Features
* Modified prompt with branch and virtual environment info
* Export `~/.local/bin`
* GPG Gitlab fix 

vim
---

### Packages (start)
* [ALE](https://github.com/dense-analysis/ale) 
* [fugitive](https://github.com/tpope/vim-fugitive)
* [FZF](https://github.com/junegunn/fzf.vim) `<\FZF>`
* [interesting-words](https://github.com/lfv89/vim-interestingwords) `<\k>`
* [lightline](https://github.com/itchyny/lightline.vim)
* [minimap](https://github.com/severin-lemaignan/vim-minimap) `<\mm>` `<\mc>` `<\mt>` (requires `vim-nox`)
* [NERDTree](https://github.com/scrooloose/nerdtree) `<\tt>` `<\tn>` `<\tf>`
* [NERDCommenter](https://github.com/scrooloose/nerdcommenter) `<\cc>` `<\cu>`
* [obsession](https://github.com/tpope/vim-obsession)
* [python-mode](https://github.com/python-mode/python-mode)
* [solarized](https://github.com/altercation/vim-colors-solarized)
* [tagbar](https://github.com/majutsushi/tagbar) `F8` (requires `exuberant-ctags`)
* [todo](https://github.com/Dimercel/todo-vim) `F5`
* [vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator) `Ctrl-hjkl`

### Packages (opt)
* [Syntastic](https://github.com/scrooloose/syntastic)

### Features
* Use solarized dark theme for the terminal for better compatibility
* Paste node `F2`
* Arrow keys move as normal on wrap mode, and `j` and `k` on visual mode only

tmux
----

### Features
* `Prefix` is `Ctrl-a`
* Moused enabled
* New windows a panes open in the current folder
* Open a new window in home directory `Ctrl-a + Ctrl-C`
* `glances` added to resurrect programs list
* Compatible with [FuzzyFinder](https://github.com/junegunn/fzf)
