# first-steps-with-git
Git setup guide for macOS and introduction on how to use it

> _This is just a basic collection of tasks that I perform on a new machine.
> For more, read the [git documentation](https://git-scm.com/doc)._

## Recommended tools

* [iTerm2](https://www.iterm2.com/)
* [Homebrew](http://brew.sh/)
* [Oh-My-Zsh](http://ohmyz.sh/)

## Installation

Just type `brew install git` in the terminal.

## Configuration

Configure email and name: 
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

Change default pull behavior
```
git config --global pull.rebase true
```

Configure a [better git log](https://coderwall.com/p/euwpig/a-better-git-log):
```
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```
