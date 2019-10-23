# Intro to Unity

## Unity resources + links

- [Unity website](https://unity3d.com)
- [Downloads (download unity hub)](https://unity3d.com/get-unity/download)
- [Scripting reference](https://docs.unity3d.com/ScriptReference/)
- [Unity Manual](https://docs.unity3d.com/Manual/index.html)
- [Pricing info: free, up to $100k income + funding / year](https://store.unity.com)

## Unity C# IDEs:

- unity installs visual studio (note: actually xamarin studio) by default
- you can install [Jetbrains Rider](http://jetbrains.com/rider/)
- or [Resharper](https://www.jetbrains.com/resharper/) if you're on windows and use (full) visual studio
- Jetbrains IDEs cost money, [but you can get them for free while you're a student](https://www.jetbrains.com/student/)

## Link to this tutorial:

We'll be livecoding some stuff, and you can checkout + pull from one of the following repositories that we'll be making at the 1st programming meeting:

- Wed 10/23/19: [https://github.com/SeijiEmery/intro-to-unity](https://github.com/SeijiEmery/intro-to-unity)

## How to install git and clone / pull

### Github desktop: 

- [Download Github desktop](https://desktop.github.com)
- Clone this repository: `https://github.com/SeijiEmery/intro-to-unity.git`
- Click 'sync' to pull changes

### How to clone + pull from commandline:

- clone the repo: `git clone https://github.com/SeijiEmery/intro-to-unity.git && cd intro-to-unity`
- run this every time I commit and you want to pull changes: `git pull`

### Install commandline: Mac OS

- [install brew, a package manager for mac os](http://brew.sh)
    - (you can just open terminal and run this): 
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install`
    - (you *may* need to install xcode commandline tools, if it asks you)
- Open terminal and run:
    - `brew install git`

### Install commandline: Linux

- you should already have git installed
- if not, and you're on eg. debian, run
    - `apt-get install git`
- (or equivalent for whatever your package manager is)

### Install git on windows:

- you probably just have to install from [https://git-scm.com/downloads](https://git-scm.com/downloads)
- windows does have *a* package manager: [https://chocolatey.org](https://chocolatey.org)
- and alternatively you can just [install + run WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10), which gives you a linux environment
- but if you know how to do this you probably don't need help installing git :)

## Other free stuff:

- [github developer pack](https://education.github.com/pack) (mostly good if you're doing web stuff and want free AWS / digital ocean / azure credits at some point. don't activate these if you don't need them)
- [sublime text](http://sublimetext.com) (great text editor, and de facto free; will guilt trip you into buying it eventually when you graduate / get a job / make money)
- [sublime merge](http://sublimemerge.com) (ditto but you're stuck with light mode :(. only a moderately okay git client (I'd recommend using github desktop instead), but it's stellar for resolving merge conflicts. We'll cover git and merging later at the second meeting)
- [visual studio code](https://code.visualstudio.com) (microsoft's sublime clone. Also a very good text editor. I'd recommend installing and using both this and sublime, as they're good at slightly different things. Think of both of these as your swiss army knives; you should be using a full IDE to write eg. c#)

## Stuff I'm using:

- Unity + UnityHub
- Rider [with sublime keybindings](https://plugins.jetbrains.com/plugin/12551-sublime-text-keymap) (partly customized so I have cmd+D)
- [iTerm2](https://www.iterm2.com), with a key to hide / show it bound to opt+space (note: similar to cmd+space for spotlight; I use both *constantly*)
    - I'm running [fish (stands for "friendly interactive shell")](https://fishshell.com) instead of bash. Fish is unfortunately not entirely compatible with bash (for better shells that are see [zsh](https://ohmyz.sh)), but what fish does have is very good autocomplete and really good defaults without having to install tons of plugins. 
    - Specifically, fish gives me the command autocomplete + syntax highlighting in my shell, and iTerm2 gives me better font rendering and some other nice bells and whistles (like a dedicated keybinding to show / hide iterm2 windows)
- [Magnet](http://magnet.crowdcafe.com), a $1 app that gives me really good, win10-esque window snapping on mac os (arguably with better keybindings). Not sure if I'll use this much, but it's very handy :)
