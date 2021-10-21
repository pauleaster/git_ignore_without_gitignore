# Ignore files in git without using .gitignore

## tldr
Place files to be ignored in `.git/info/exclude`

## Why
These files are ignore, but it doesn't effect your remote repo. Therefore you can add in `.vscode` to this folder and not have to worry about getting out of sync with your remote.

## Source
https://stackoverflow.com/a/653458/1542485
