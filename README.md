# ~/.dotfiles

### Using Git and the bootstrap script
You can clone the repository wherever you want. (I like to keep it in `~/.dotfiles`).

The installation step requires the [XCode Command Line Tools](https://developer.apple.com/downloads), although you *should* be prompted to install these if you don't have them installed already.

The bootstrap script *attempts* to backup existing dotfiles in your HOME directory, but to be safe you should probably make your own copy...

```sh
git clone https://github.com/matt3188/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```
This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.