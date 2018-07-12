# essential-terminal

##  Git

### Delete branches that have been merged into `dev`

    git branch --merged dev | egrep -v "^\*|master|dev|develop" | xargs git branch -d
    # create git alias
    git config --global alias.cleanup '!git branch --merged dev | egrep -v "^\*|master|dev" | xargs git branch -d'

### [gitignore.io](https://www.gitignore.io/docs)

##  Mac
* [iTerm2](https://www.iterm2.com/)
* [Oh My ZSH](https://ohmyz.sh/)
