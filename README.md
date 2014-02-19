# My dotfiles
> This is my folk from the Eduarbo's dotfiles (https://github.com/eduarbo), so thanks for sharing them man.
> I wanted to keep this simple, functional, and styled.

# Install
    git clone https://github.com/tonatiuh/dotfiles.git ~/.dotfiles && cd ~/.dotfiles && source bin/dotfiles
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    vim +BundleInstall +qall

# Bash features
* Up/ down arrow partial search in history
* Bash Completion
* Styled git log
* User profile shows the current branch (when in a git repo)

# Vim overall features
* Autocomplete
* Look up for files by typing ctrl+p
* Open Nerdtree by typing ctrl+n
* Nerdtree remains consistent in all the tabs
* Support for auto close quotes, parenthesis, curlybraces, etc
* Comment code lines by typing gcc
* Pressing the semi-colon key is recognized as colon (is faster to type)
* Two times j key jj is goes from "insert mode" to "visual mode"
* jk goes from "insert mode" to "visual mode" and also saves the file
* Tabs like chrome (ctrl+t new tab, ctrl+w closes tab)
* :Rename "new_file_name" (without quotes) command allows you to rename the current file
* :Remove command allows you to delete the current file
* Change two simple quotes to double quotes by typing c s ' " (in visual model
  over the first simple quote) [ more info ](https://github.com/tpope/vim-surround)
* Code autoalignation by the equal sign ("="), select the code in visual mode, then press Ctrl+a

# File support
* HAML
* Ruby
* Coffeescript
* Javascript
* SASS

# Git aliases
    l -> log
    ps -> push origin HEAD
    f -> fetch
    df -> diff
    addp -> add --patch
    dfc -> diff --cached
    last -> diff HEAD^
    softback -> reset --soft HEAD
    mergecommit -> merge --no-ff
    depintegration -> !git push origin integration && git push integration HEAD:master
    st -> status -sb

# Vim used theme
> Jelly beans

![vim] (http://oi57.tinypic.com/1zg57rr.jpg)

# Bash profile
![bash profile] (http://oi58.tinypic.com/wkqomr.jpg)

# Git log
![git log] (http://oi61.tinypic.com/29vdted.jpg)
