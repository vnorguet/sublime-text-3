# Customized Sublime Text 3 config

## Main targets:

* Mainly Ruby and Rails development

It also includes some tools and stuff for other languages:

* JSON formatter
* MYSQL formatter
* Git stuff
* Customized bar (icons, background, ...)

To have a good overview of packages, check "Installed Package" folder

## Installation

* Install Package Control first : [Link](https://sublime.wbond.net/installation)
* Clone the repository

## Notes

* Sublime text uses tabs for their config files. `sublime-text-3/Packages/User/Package Control.sublime-settings` changes on each plugin install and updates. To be able to version it easily, allow tabs in git:
    - In `.git/info/attributes`, add `*.sublime-settings  filter=tabspace`, as mentionned here: [Link](http://stackoverflow.com/questions/2316677/can-git-automatically-switch-between-spaces-and-tabs)
    - run `git config --global filter.tabspace.smudge 'unexpand --tabs=4 --first-only'`
    - run `git config --global filter.tabspace.clean 'expand --tabs=4 --initial'`
