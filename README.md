# Terminal setup

<img src="ScreenshotNew.png" width="500">
<img src="Screenshot.png" width="500">

- [iTerm2](https://www.iterm2.com/) instead of the Stock terminal Mac app
- [oh-my-zshell](https://github.com/robbyrussell/oh-my-zsh)
- [rbenv](https://github.com/rbenv/rbenv) and [rvm](https://rvm.io/) (on different computers - please only install one of them)
- [Solarized Dark](http://ethanschoonover.com/solarized) for the terminal colors
- [powerline-shell](https://github.com/milkbikis/powerline-shell) to get those cool path bars. I usually hide the host name and the user, before running `python ./setup.py install`, edit the config file and comment out `username`, `hostname`. 
  - `cd ~/.oh-my-zsh/`
  - `mkdir felix`
  - `cd felix`
  - `git clone https://github.com/b-ryan/powerline-shell`
  - `cd powerline-shell`
  - `sudo python setup.py install`
- [Meslo Powerline Font](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf) as you need a font that supports the directory characters for `powerline`
- [z](https://github.com/rupa/z) an amazing tool to quickly jump between projects. Like [Alfred](https://www.alfredapp.com/) but for your Terminal reduced to folder search only
- [Install Powerlevel10](https://github.com/romkatv/powerlevel10k#oh-my-zsh)
- `subl .` command a lot to quickly open a specific folder in Sublime Text. This is what I use to edit my `fastlane` configuration
- `echo "gem: --no-document" >> ~/.gemrc` to stop installing docs every time you install a gem
- `o .` or `o filename.js` to open files (see [KrauseFx/dotfiles](https://github.com/KrauseFx/dotfiles))
- Settings -> Profiles -> Keys -> Load Preset -> Natural Text Editing
- Enable the `Show proxy icon in window title bar` option to show the folder on the window title bar for right click and drag & drop gestures
- `Profiles` -> `Advanced` -> `Semantic History` -> `Open with editor...` -> `Sublime Text 3`
- `Keys` -> Replace `Cycle Tabs ...` with `Next Tab` and `Previous Tab`
