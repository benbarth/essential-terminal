# essential-terminal

## Git

### Delete branches that have been merged into `dev`

$ `git branch --merged dev | egrep -v "^\*|master|dev" | xargs git branch -d`

or add git alias

$ `git config --global alias.cleanup '!git branch --merged dev | egrep -v "^\*|master|dev" | xargs git branch -d'`
