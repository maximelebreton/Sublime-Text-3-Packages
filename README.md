Sublime Text 3 Packages Boilerplate for Front End Developpers
=======================

## What's that ?
- A collection of useful plugins for Front End Developpers
- A "ready to code" working space for your fresh installs
- A time saver if you have to install these essential plugins (30 seconds!)

All the Packages are cloned in the repository as independant [submodules](http://git-scm.com/book/en/Git-Tools-Submodules), so you'll **get always the last version**!  

## How to install
Open your Sublime Text Packages folder:
```no-highlight
Preferences -> Browse Packages
```

Clone the repo:
```no-highlight
git@github.com:maximelebreton/Sublime-Text-3-Packages.git
```

Init the submodules:
```no-highlight
git submodule update --init
```

And that's all.

## How to update

In your repo, launch this command
```no-highlight
git submodule foreach git pull
```
