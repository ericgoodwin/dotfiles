Installation
============

Prerequisites
-------------

* Git (1.7+)
* Ruby (1.9 recommended) and RubyGems
* Tree

Optional, but recommended:

* ZSH
* [rbenv](http://rbenv.org)
* [Homebrew](http://mxcl.github.com/homebrew/) (OS X only)


Bootstrapper
------------



The bootstrapper depends on three things: ruby, rake, and bundler. Assuming you
have ruby and ruby gems installed on your system: `gem install rake bundler`.

Then:

``` bash-session
$ gem install rake bundler
$ ruby -e "$(curl -fsSkL raw.github.com/mxcl/homebrew/go)"
$ brew update
$ brew install git tree rbenv ruby-build
$ curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
$ zsh < <( curl https://raw.github.com/ericgoodwin/dotfiles/master/bootstrap.sh )
```

Don't worry, all your old files will be backed up!


Stay Updated
------------

Run the bootstrapper again!

``` bash-session
$ ~/.dotfiles/bootstrap.sh
```

Plugins
=======

Installed plugins and syntax files.

* Ack
* Clojure
* Cocoa
* CoffeeScript
* CSS-color
* CtrlP
* Fish
* Gist
* Haml
* Handlebars
* Histwin
* Indent Guides
* Jade
* Javascript
* Markdown
* Nerdcommenter
* Nu
* Pastie
* Powerline
* Pathogen
* Racket
* Rails
* Rainbow Parenthesis
* Repeat
* Ruby
* Slim
* Snipmate
* Stylus
* Surround


iPad
----

Rudimentary support for vim on the iPad has been added via usage of the
`xterm-ipad` `$TERM` value. In this mode `<Tab>` is `<Esc>` and `,<Tab>` is
`<Tab>`.


Shell
=====

Most of the shell junk is setup to work in both zsh and bash. Bash users should
see [.bash_profile](https://github.com/ericgoodwin/dotfiles/blob/master/.bash_profile)
and [.bash_prompt](https://github.com/ericgoodwin/dotfiles/blob/master/.bash_prompt).


Aliases
-------

Check out [.aliases](https://github.com/ericgoodwin/dotfiles/blob/master/.aliases)


Scripts
-------

Additional useful scripts bundled:

* ack
* bookmarklet

Fonts
=====

A modified version of Menlo is available in `.fonts` for use with [powerline.vim](https://github.com/Lokaltog/vim-powerline/).


Git
===

I've included some handy git script additions as well as configution changes.
Have a look at
[.gitconfig](https://github.com/ericgoodwin/dotfiles/blob/master/.gitconfig) to see
various aliases and settings.

Additional scripts (see [.scripts](https://github.com/ericgoodwin/dotfiles/tree/master/.scripts/) directory for source):

* git-publish-branch
* git-rank-contributors
* git-rbranch
* git-review
* git-show-merges
* git-wtf


Configurations
==============

Sensible configurations exist for:

* Ack
* Awesome Print
* RubyGems
* Git
* IRB
* TMUX

