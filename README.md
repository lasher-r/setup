#Macos

* [Brew](##Brew)
* [zsh](##zsh)
* [vim](##vim)
* [vscode](##vscode)
* [global packages](##npm -g)

## Brew

### Install

`xcode-select --install`

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

`brew install homebrew/cask`

###  packages

`brew install zsh docker fasd nvm tree curl wget git-flow thefuck`

`brew cask install visual-studio-code postman google-chrome`

`brew tap homebrew/cask-fonts`

`brew cask install font-fira-code`

## zsh

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

`chsh -s $(which zsh)`

`cp ~/.zshrc ~/.zshrc.bak && cp dot_zshrc ~/.zshrc`

## vim

`cp ~/.vimrc ~/.vimrc.bak && cp dot_vimrc ~/.vimrc`

`git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

`vim +PluginInstall +qall`

## vscode

### packages: 

 * patbenatar.advanced-new-file
 * nwhatt.chai-snippets
 * yummygum.city-lights-icon-vsc
 * compulim.vscode-clock
 * wesbos.theme-cobalt2
 * msjsdiag.debugger-for-chrome
 * dsznajder.es7-react-js-snippets
 * xabikos.javascriptsnippets
 * chris-noring.node-snippets
 * wallabyjs.quokka-vscode
 * eamodio.gitlens

### Settings:
    
settings>search 'font'
    
```
"editor.fontFamily": "'fira code'"
"editor.fontLigatures": true
"window.restoreWindows": "none"
```

search 'title'

window:title = ${rootName}${separator}${activeEditorShort}

keyboard shortcuts:

new untitled file: ctrl cmd n
advanced new file: cmd n

## npm

`npm i -g eslint git-open node-inspector nodemon prettier`



