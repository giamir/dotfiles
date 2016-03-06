# dotfiles

My personal home dotfiles, to share it across computers.

## How to set it up

First install homesick:

```gem install homesick```

Now create a "castle". A castle is a collection of dotfiles.

```homesick generate ~/dotfiles```

This creates a git repo with a /home folder inside. Just put your dotfiles / dotfolders in there.

Now install the castle with homesick.

```homesick clone git@github.com:giamir/dotfiles.git```

Now let homesick do its magic.

```homesick symlink dotfiles```

All the dotfiles from within this castle will be symlinked.



## Thanks

Much of my configuration is inspired by [Thoughtbot's dotfiles](https://github.com/thoughtbot/dotfiles).<br>
In particular many thanks to [Chris Toomey](https://github.com/christoomey/dotfiles)

It is designed to work with [homesick](https://github.com/technicalpickles/homesick) which handles all my symlinking for me automatically.<br>
Thanks to Joshua Nichols for this awesome gem.

Finally thanks to [Leo Allen](https://github.com/pitchinvasion), one of my coaches at Makers Academy, to inspired me with his [dotfiles configuration](https://github.com/pitchinvasion/home-files).

### Get Inspired
An amazing collection of home dotfiles to have a look at.<br>
[github dotfiles](http://dotfiles.github.io/)
