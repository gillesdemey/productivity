# Table of Contents
* [Preface](#preface)
* [Terminal](#terminal)
  * [Homebrew](#homebrew)
  * [iTerm2](#iterm2)
	* [iTerm2 themes](#iterm2-themes)
	* [Fixing iTerm2 key bindings](#iterm2-keybindings)
  * [Oh-my-zshell](#oh-my-zshell)
	* [Zshell in tmux](#zshell-tmux)
	* [Zshell Syntax Highlighting](#zshell-syntax)
  * [Nano syntax highlighting](#nano-syntax)
* [Applications](#applications)
	* [Sublime Text](#sublime-text)
		* [Sublime Package Manager](#sublime-package-manager)
	* [ClipMenu](#clipmenu)
	* [Spectacle](#spectacle)
	* [Alfred](#alfred)
	
# Preface<a name="preface"></a>

The intention of this list is to help you get on your way and to encourage you to check out these utilities on your own and discover how they can help you to be more productive. 

I won't be discussing anything in depth, as I think that everyone has to discover for themselves how they can take advantage of what is listed below.

I compiled this list mainly for myself, but anyone can benefit from it.

If you have any questions, you can send them to [hello@gillesdemey.be](mailto:hello@gillesdemey.be).

If you have any remarks, see a mistake or if you want to contribute to this list, feel free to send me a pull request.

**Note:** All of these applications and utilities are created specifically for either **Mac OS** and/or **Linux**.

# Terminal<a name="terminal"></a>

Any developer worth his salt will spend loads of time in the terminal, these utilities will mostly help you get things done faster, and with less headaches.

## Homebrew<a name="homebrew"></a>
[http://brew.sh/]()

Homebrew enables you to install a plethora of useful software and utilities very much like aptitude does on Linux with the exception that it builds the software specifically for your platform.

## iTerm2<a name="iterm2"></a>
[http://www.iterm2.com/#/section/home]()

iTerm2 is a must-have for anyone who works a lot in the terminal, it has loads of useful functions and customizable settings.

### iTerm2 themes<a name="iterm2-themes"></a>
[https://github.com/mbadolato/iTerm2-Color-Schemes]()

Useful for anyone who isn't content with the default themes that are shipped with iTerm2.

My personal favorite is **Monokai Soda**.

### Fixing iTerm2 key bindings<a name="iterm2-keybindings"></a>
[http://elweb.co/making-iterm-2-work-with-normal-mac-osx-keyboard-shortcuts/]()

This makes it easier to navigate in the CLI, using sane key bindings to move around.

## Oh-my-zshell<a name="oh-my-zshell"></a>
[https://github.com/robbyrussell/oh-my-zsh]()

A better shell implementation than bash, backwards compatible with bash scripts so you don't have to worry about compatibility. 

There are lots of plugins and some functionality that come out-of-the-box with Oh-my-zshell.

**note:** If you're on linux, make sure to install zsh first using `sudo apt-get install zsh`

### Zshell in tmux<a name="zshell-tmux"></a>

If you're using tmux, make sure you add `set-option -g default-shell /bin/zsh` to your `~/.tmux.conf` or `/etc/tmux.conf` file.

Then kill your tmux session so your shell can reload.

`killall tmux; tmux`

### Zshell Syntax Highlighting<a name="zshell-syntax"></a>
[https://github.com/zsh-users/zsh-syntax-highlighting]()

Syntax highlighting for your terminal commands, useful if you write a lot of long statements.

## Nano syntax highlighting<a name="nano-syntax"></a>
[https://github.com/nanorc/nanorc]()

*If you use Vim or Emacs, feel free to ignore this.*

This provides some useful syntax highlighting for many languages when using nano.

**Note:** If it doesn't work, remove all `syntax` and `includes` from `/etc/nanorc`.

# Applications<a name="application"></a>

## Sublime Text<a name="sublime-text"></a>
[http://www.sublimetext.com/]()

My preferred code editor is Sublime Text. There are many packages available that extend it's abilities and to ultimately help you to become a code ninja.

As a beginner, I encourage you to check out these screencasts by Jeffrey Way. They are well worth your time.

[http://net.tutsplus.com/articles/news/perfect-workflow-in-sublime-text-free-course/]()

### Sublime Package Manager<a name="sublime-package-manager"></a>
[https://sublime.wbond.net/installation]()

A package manager for Sublime Text. It's mandatory if you want to add extra functionality.

## ClipMenu<a name="clipmenu"></a>
[http://www.clipmenu.com/]()

My preferred clipboard history manager, it's free, supports many types of data and has some useful features like custom actions and snippets.

## Spectacle<a name="spectacle"></a>
[http://spectacleapp.com/]()

Easy to use window manager with customizable keyboard shortcuts.

## Alfred<a name="alfred"></a>
[http://www.alfredapp.com/]()

Alfred is great, The Verge has a great article covering it.

[http://www.theverge.com/2012/12/3/3718546/verge-at-work-alfred-computer-shortcuts]()

And it has a hat for a logo, what's not to like?

---

**Note:** This is a living document, whenever I come across something interesting I'll be likely to add it once I've used it long enough to make up my mind wether or not to include it in this list.
