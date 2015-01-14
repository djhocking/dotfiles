# hocking does dotfiles

## dotfiles

Your dotfiles are how you personalize your system. These are mine.

If you're interested in the philosophy behind why projects like these are
awesome, you might want to [read Zach Holman's post on the
subject](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/).

Other good dotfiles and information can be found at:

* [Getting Started with Dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789)
* [GitHub does Dotfiles](https://dotfiles.github.io/)
* [Ryan Bates Dotfiles](https://github.com/ryanb/dotfiles)

## install

Run this:

```sh
git clone https://github.com/djhocking/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./bootstrap.sh
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.

## thanks

This README is based on those of [Zach Holman] (https://github.com/holman/dotfiles), which was useful for me getting started with installing dotfiles. I forked [Jeff Walker's](https://github.com/walkerjeffd)
[dotfiles](http://github.com/ryanb/dotfiles) after he introduced me to dotfiles.
