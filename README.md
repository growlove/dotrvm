# dotrvm
## A simple rvm dotfiles generator

dotrvm is a shell script that generates .ruby-version and .ruby-gemset files in the current directory (with overwrite verification if files exist).

### Usage
dotrvm -h/--help

dotrvm \[ruby version\] \[gemset name\]

### Example
dotrvm ruby-2.2.1 my_little_project