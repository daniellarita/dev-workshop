# dev-workshop

## Let's Git it on
#### Download and install Git
This is a large file, so hopefully you've already done this. If not, try grabbing it from someone who has via "Air Drop". Probably faster than downloading from the interwebs.
```
http://git-scm.com/download/mac
```

#### Download and install Github Mac Client
This is optional and you can do everything from the command line using the `git` command, but some people prefer using a visual client. It doesn't hurt to have it.
```
https://desktop.github.com/
```

## Terminal Stuffs

#### Install iTerm2
OSX has a built in Terminal/Command line app, but it's not as nice as iTerm. So download & install it. You'll be very happy you did.
```
https://www.iterm2.com/
```
Make sure you drag the application icon from your "Downloads" folder to your "Applications" folder on your Mac. If you don't know what that means or how to do that, ask one of the nerds in the room.

You may also want to "Keep in Dock" the iTerm app, so that its always there and easily accessible.

#### Zsh is good for you
Change your default bash to Zsh. What the hell does that mean? Without getting too much into it, it just gives you more tools and its generally smarter and better at things than `bash`. So let's tell OSX to use `zsh` as the default shell command.
```
chsh -s $(which zsh)
```

#### Make our Command line useful & pretty
Somebody spent a lot of time putting together a bunch of very useful things to make your Command line all beautiful and useful and also provide you with tons of shortcuts so you don't have to type as much. Thanks Mr. Holman.
```
git clone https://github.com/holman/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```

We'll also creat this file in our home directory so we can put some of our own shortcuts and commands.
```
touch ~/.localrc
```

For example, here is what I have inside my `.localrc` file:
```
https://gist.github.com/i8ramin/622f5703f0089c20733a
```

## Sublime is pretty neat
Sublime is a very nice, minimal and extremely powerful editor. Let's install it!
```
http://www.sublimetext.com/3
```

#### Enable `subl` from the Command line
```
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```

And here are my own personal Sublime settings
```
https://gist.github.com/i8ramin/2e6285ca122f8b291be5
```
